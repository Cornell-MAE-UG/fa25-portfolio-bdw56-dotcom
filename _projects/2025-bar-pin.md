---
layout: project
title: Optimizing Rigid Rod and Pin Setup
description: In a confined space, find the most mass and highest height that a linear actuator can push a weight to along a rigid bar
technologies: [GoodNotes Drawings, Desmos, Google Sheets]
image: /assets/images/linear-actuator-diagram.jpg
---

I needed to design a mechanism to lift max possible weight to highest possible height with:
- 2D design of 150cm long and 50 cm tall space
- A rigid bar of fixed length (your choice)
- 3 pin supports of which two are pinned to the ground
- A linear actuator (picked from a catalog) with only its max force

I worked on this project with a friend, Hayden in the same class.

After finding an equation to find the mass and height of the mass (seen in the picture) by using the moment around pin 1, I first started plotting values into google sheets in order to see if there were any values that I should keep at a constant value (also keep in mind that I presumed the actuator always made a 90 degree with the rod since the actuator could rotate around the pin). From this testing, I found that the length of the bar should stay at 1.5m (the max horizontal distance). Also, after talking with Hayden, we came to the conlcusion that the bar should be at an angle where the bar does not overeach the max height and then we can just change the height of the mass to find max mass and max height (less variables). As seen above, this theta value came out to be 19.47 degrees. Finally, looking through the catalog, the actuator I chose was IMA33 because it had a large max force (allowing for more mass) of 45.82 kN.

Then, Hayden was able to plug this into Desmos to see how x affects the max height and the max mass. We found that as mass is closer to pin 1, the max amount of mass approaches infinity however the height is obviously not high. When we approach the max height of 50cm however, the mass continues to decrease. So therefore, we thought that to get the max height and max weight, it would be smart to just take the midpoint of the bar which came to be 70.71 cm along the horizontal axis. 

Therfore, by plugging in these values the max mass = 10519.92 kg and max height = 24.998 cm.

