---
layout: project
title: Optimizing Rigid Rod and Pin Setup
description: In a confined space, find the most mass and highest height that a linear actuator can push a weight to along a rigid bar
technologies: [GoodNotes Drawings, Desmos, Google Sheets]
image: /assets/images/linear-actuator-diagram.jpg
---

Part 1: I needed to design a mechanism to lift max possible weight to highest possible height with constraints:
- 2D design of 150cm long and 50 cm tall space
- A rigid bar of fixed length (your choice)
- 3 pin supports of which two are pinned to the ground
- A linear actuator (picked from a catalog) with only its max force

I worked on this project with a friend, Hayden in the same class.

Since I am only considering this bar in the xy plane, this only has 3 degrees of freedom since it can rotate into/out of the xy plane, move along the x-axis, and move along the y-axis.

After finding an equation to find the mass and height of the mass (seen in the picture) by using the moment around pin 1, I first started plotting values into google sheets in order to see if there were any values that I should keep at a constant value (also keep in mind that I presumed the actuator always made a 90 degree with the rod since the actuator could rotate around the pin). From this testing, I found that the length of the bar should stay at 1.5m (the max horizontal distance). Also, after talking with Hayden, we came to the conlcusion that the bar should be at an angle where the bar does not overeach the max height and then we can just change the height of the mass to find max mass and max height (less variables). As seen above, this theta value came out to be 19.47 degrees. Finally, looking through the catalog, the actuator I chose was IMA33 because it had a large max force (allowing for more mass) of 45.82 kN.

Then, Hayden was able to plug this into Desmos to see how x affects the max height and the max mass. We found that as mass is closer to pin 1, the max amount of mass approaches infinity however the height is obviously not high. When we approach the max height of 50cm however, the mass continues to decrease. So therefore, we thought that to get the max height and max weight, it would be smart to just take the midpoint of the bar which came to be 70.71 cm along the horizontal axis. 

Therfore, by plugging in these values the max mass = 10519.92 kg and max height = 24.998 cm.

Part 2: Now, the bar in your mechanism is no longer rigid. In fact, it is now best described as
a beam which bends due to the combined action of the weight and the actuator force. My objective for this part was to a) find the maximum deflection in your beam and b) choose a beam design (cross-section, material) such that its vertical deflection is below 2% of its length and is the most mass-efficient possible. 

Same as above: Since I am only considering this bar in the xy plane, this bar has 3 degrees of freedom.

In my setup above, I showed how mass is greatest (and largest in height) when at the midpoint of the beam at the maximum height within the constraints. For this reason, I am determining the deflection of the bar with a point load right in the middle of the bar. From the textbook, this ymax value happens right in the middle of the bar with magntiude -P/48EI -- in our situation P = mgcos(theta) therefore making the equation: -mgcos(theta)/48EI. Since I am the one making the cross-sectional area (affecting I) and the material (affecting E), I cannot solve for the maximum deflection yet. However, since in part b) of the objectives it asks for an E and I value that leads to no more deflection than that of 2% of the length, I will 0.02L equal to the max deflection of the beam. This value comes out to be 3 cm.

When it comes to finding the most mass-efficient cross-section (smaller area and therfore smaller mass), I thought of a circle cross-section. However, to check this with a rectangle, I found the I of a circle in terms of its diameter and that of a rectangle. To be more mass-efficient, the shapes I/A must be greater than another. If a circle's diameter and a rectangle's height were to be the same value, then I/A of a circle is porportional to 1/16 and I/A of a rectangle is porportional to 1/12 making a rectangle more mass-efficient.

I chose to use a sturdy material because this helps max sure that the deflection doesn't exceed 3 cm. However, I also wanted to take into condiseration the density of the material since this leads to a more "mass-efficient" support. Therefore, I chose either structural steel with a Young's Modulus of E = 200GPa and density = 7860 kg/m^3 (w/ L =1.5, density = 11790 kg/m^2) or titanium with a Young's Modulus of E = 115GPa and density = 4730 kg/m^3 (w/ L =1.5, density = 7095 kg/m^2). Since the ratio of Young's Modulus to desnity is greater for that of titanium, I chose this material. With an E=115GPa, theta = 0 (since this is where the weight will be greatest meaning that the I of the beam still has to be supportive of the weight there), m = 10519.92 kg, and ymax= 3 cm, the minimum value for the moment of interia is 6.2256x10^-7.

Using a rectangle as the cross section (I = 1/12bh^3), I want to make a cross sectional beam with a height that is at least 2 times as large as its base since height has more of an impact on the moment of inertia but you couldn't put anything on a beam with a really thin base (a larger height also minimizes area and therefore mass). Therefore, Imin = 2/3b^4. With the Imin value found above, my minimum base value would be 3.109 cm making my height equal to 6.217 cm. 

In reality, you would not choose a cross-section that has the minimum moment of intertia since there is a strong possibility that something happens to the beam, forcing the Imin to not be sufficient enough to keep the delfection under 3 cm. Therefore, a greater area would more than likely be chosen (depending on factor of safety) even though the Imin value leads to the most mass-efficient model (smallest area with Height = 2 * Base). 

![Photo of diagram]({{ "/assets/images/linear-actuator-diagrampt2.jpeg" | relative_url }}){: .inline-image-l}

