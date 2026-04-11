---
layout: project
title: MAE2250 Open Design Project
description: Group project focusing on the lanternfly infestation and their effects on the grape industry 
technologies: [GoodNotes]
image: /assets/images/ODP_Initial_Drawing.PNG
---
## Table of Contents
[Client Pitch](#client-pitch:-a-mechanical-approach-to-quantifiable-spotted-lanternfly-egg-mass-control)<br>
[Functional Prototype](#functional-prototype)
<br>
<br>
<br>
<br>
<br>

## Client Pitch: A Mechanical Approach to Quantifiable Spotted Lanternfly Egg Mass Control

**Team:** Buzzkill (Ethan Moger, Bennett Wehibe, Adair Bluman, Trevor Crouse, Allen Liu)   
**Client(s):** Cornell CALS Extension | E\&J Gallo Winery | National Grape  

### Problem Statement

Current control methods for the spotted lanternfly (SLF) fail to ensure destruction or provide a reliable way to quantify how many egg masses were destroyed. Eggs are protected by a waxy coating and 68.5% are adhered to rough surfaces such as tree bark (2); if scraped onto the ground, they can still hatch if not destroyed. Our challenge is to develop a mechanical system that ensures destruction of egg masses across various surfaces and enables growers to numerically analyze the system’s success.

### Impact
Vineyards reduce SLF populations at the source by targeting egg masses, which prevents the emergence of 30 to 50 insects per egg mass (1). Verifying destruction allows vineyards to quantify population reduction, improving confidence in control protocols and providing a scalable solution.

### Proposed direction
###### Jaw-Bucket Egg Removal and Containment System   
Jaws scrape off and collect egg masses. An internal compartment stores eggs for later disposal.

<u>Method of Usage: </u>
 - Uses a trigger on a handle to create a high mechanical advantage to close the jaws
 - Jaws scrape against the surface, removing and collecting the egg masses
 - Uses a sliding door container to allow egg masses to fall in but not back out onto the ground

<u>Improvements Over Past Solutions: </u>
 - More efficient and comfortable than scraping with a card, but still hand-held chemical free
 - Enables easy counting of egg masses in the bucket to numerically evaluate the device's impact

By the end of the semester, we will have a tested prototype showing proof of concept that efficiently removes and collects simulated egg masses off various surfaces and requires little force input to operate.

### Key Risks / Unknowns

- Risk 1: Operation of this device can be labor and time intensive for farmers with tight margins     
*Importance/Testing:* If too slow, vineyards won’t adopt it; test by finding time per egg mass
- Risk 2: Damage to grapevines or grapes when the egg masses are scraped off    
*Importance/Testing:* If it damages vines, they may be unusable; inspect after repeated use to test
- Risk 3: Interference with growing regulations by introducing a new device into the vineyard   
*Importance/Testing:* If it violates regulations, it can’t be used; test by checking growing standards

### Questions For the Client

1. <u> Do egg masses vary significantly in size, thickness, or shape throughout the season?</u>   
*Decision Affected:* Jaw opening width, bucket size, and shape of teeth on the jaw
2. <u> What surfaces are the most difficult to remove the egg masses from?</u>   
*Decision Affected:* Material of our scraper (some surfaces might require more or less force)
3. <u> Are eggs often laid in places throughout vineyards that can’t be reached by hand?</u>   
*Decision Affected:* Impacts whether or not the tool is extendable/flexible to enable greater reach

### References

1. J Keller, J Rost, K Hoover, J Urban, H Leach, M Porras, B Walsh, M Bosold, D Calvin. 
“Dispersion Patterns and Sample Size Estimates for Egg Masses of Spotted Lanternfly (*Hemiptera: Fulgoridae*),” Environmental Entomology, Volume 49, Issue 6, December 2020, Pages 1462–1472. <https://doi.org/10.1093/ee/nvaa107>

2. Houping Liu, Oviposition Substrate Selection, Egg Mass Characteristics, Host Preference, and 
Life History of the Spotted Lanternfly (Hemiptera: Fulgoridae) in North America, Environmental Entomology, Volume 48, Issue 6, December 2019, Pages 1452–1468, <https://doi.org/10.1093/ee/nvz123>

### Figure
![Initial Drawing]({{ "/assets/images/ODP_Initial_Drawing.PNG" | relative_url }}){: width="575px"}
Figure 1: Mechanical Jaw Bucket Design with Internal Compartment
{: style="display: block; text-align: center; font-size: 0.8em; color: black;"}

<br>

## Functional Prototype
![Initial Drawing]({{ "/assets/images/Table1pt1.png" | relative_url }}){: width="575px"}
![Initial Drawing]({{ "/assets/images/Table1pt2.png" | relative_url }}){: width="575px"}


### Design Intent and Functionality:   
    We used the calculations and design estimates from our proof of concept and the feedback we received to refine our design and build our functional prototype. 
    Our bucket and jaw assembly, made out of lightweight 3D-printed plastic, is designed to hold 100 egg masses. For our first prototype, we decided to use PLA because it is cost-effective and the RPL can print it quickly. We designed the bucket to have an angled opening and curved bottom, so it works at different angles. The springs attach to the inside of the bucket and jaw, and the assembly moves with the help of the hinge and string on top.    

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 2%;">

  <div style="width: 48%; text-align: center; margin-bottom: 20px;">
    <img src="{{ '/assets/images/Figure 1.png' | relative_url }}" style="width: 100%; display: block; margin-bottom: 8px;">
    <span style="font-weight: bold; font-size: 0.75em; display: block; line-height: 1.2;">Figure 1: Bucket and Jaw Side View Closed</span>
  </div>

  <div style="width: 48%; text-align: center; margin-bottom: 20px;">
    <img src="{{ '/assets/images/Figure 2.png' | relative_url }}" style="width: 100%; display: block; margin-bottom: 8px;">
    <span style="font-weight: bold; font-size: 0.75em; display: block; line-height: 1.2;">Figure 2: Bucket and Jaw Side View Open</span>
  </div>

  <div style="width: 48%; text-align: center; margin-bottom: 20px;">
    <img src="{{ '/assets/images/Figure 3.png' | relative_url }}" style="width: 100%; display: block; margin-bottom: 8px;">
    <span style="font-weight: bold; font-size: 0.75em; display: block; line-height: 1.2;">Figure 3: Inside Bucket with Jaw Springs</span>
  </div>

  <div style="width: 48%; text-align: center; margin-bottom: 20px;">
    <img src="{{ '/assets/images/Figure 4.png' | relative_url }}" style="width: 100%; display: block; margin-bottom: 8px;">
    <span style="font-weight: bold; font-size: 0.75em; display: block; line-height: 1.2;">Figure 4: Overall Bucket and Jaw with String Attached</span>
  </div>

</div>
<br>
After feedback on our mock-up prototype, we designed a 3D-print shoulder stock attachment to the other end of the PVC pipe and attached padding on the end to further reduce user discomfort.

The handle-trigger assembly is made up of 2 pieces of 3D-printed plastic. The handle is slid onto and screwed in place to the PVC pipe. The string that operates the jaw is attached to the trigger, which slides along guide rails on the inside of the handle. 

This then yields the larger, more surface-level operation of the functional prototype in which a user squeezes the trigger to open the jaw, and then releases to scrap off an egg mass.

### Assembly Process:  
After 3D printing the parts shown above and ordering the rest of the parts from McMaster or sourcing from the Taylor Design Studio, we began the assembly process. Due to larger than expected tolerances of the RPL, we had to sand down the diameter of the PVC pipe in order for it to fit into the slots on our components. We then drilled ¼ in holes in the pipe at the locations needed to bolt the components to the pipe and run string where needed.
First, a through hole was drilled in the back of the pipe and the shoulder stock was bolted on. For consistency, will use red arrows denoting functional/mechanical motion (intended use) and blue arrows for assembly processes.

Next, we drilled holes both for the bolt attaching the handle to the pipe and also to run string from the handle to inside the pipe. 

Following this, we drilled a hole to bolt the bucket-jaw assembly to the pipe, as well as a hole before thai attachment at the top of the pipe to allow the string to exit the inside of the pipe and move towards its guide ramp on the bucket for actuation.

The subassemblies include the handle-trigger and bucket-jaw assemblies. The handle-trigger assembly can be seen through the images above, as the trigger simply slides in the handles guide rails while the string ties to it. The bucket-jaw asse

This concludes the assembly process. Below is an image of the functional prototype as built in the lab.

### Design Testing  
<u>Test One:</u>  

**Part:** Bucket and Jaw Assembly   
**What it is Testing:** Scraping/Hinging Force of the Jaw When Attached to Bucket, Durability   
**How to Perform Test:** Using spring scale, measure output force of the jaw mechanism, and using ruler measure opening gap of the jaw due to spring rest length. Then, cycle the actuating system 100 times, and measure the output force and rest length again. Observe any changes in force or rest length.   

*Test Results:*    
**Initial**
- Output force of jaw mechanism when fully open: 12.5N
- Opening gap of jaw due to spring rest length: 1.05 inches   
**After 100 cycles**
- Output force of jaw mechanism when fully open: 11.5N
- Opening gap due to jaw due to spring rest length: 1.15 inches   

**Conclusion for Next Iteration:** Opening gap increased by 0.1 inch and force decreased by 1N over 100 usage cycles. The springs we used for this prototype are too long and too prone to wear, so we will find shorter and more durable springs for the next prototype.

<u>Test Two:</u> 

**Part:** Handle/Trigger Assembly  
**What it is Testing:** Ergonomics of the handle as well as the force required to squeeze the handle.   
**How to Perform Test:** We first took images of a group member using the prototype in three different positions. One where they held the prototype upwards as if scraping egg masses from above, one straight in front, and one downwards. The RULA (Rapid Upper Limb Assessment) was completed. We used CUErgo (1) to guide us through the process of conducting this test, with our client feedback providing information we could use to estimate how long the user would be in each position.   

*Test Results:*   
- Low position: scored a 3
- Middle position: scored a 4
- High position: scored a 4
- Total RULA score: 3.9
- Took over 40 pounds of force to squeeze handle when not perfectly aligned   

**Conclusion for Next Iteration:** Our goal for this prototype was to get a RULA score below 5, which means that users will be at a low risk of MSD (musculoskeletal disorders) from our device, based on the below graphic from Ergo-Plus (2). See images below for further information. We calculated our prototype to have a total RULA score of 3.9, indicating low risk and achieving our goal of <5. For our next prototype, we aim to keep our score at or below 3.9. The handle and trigger will also be redesigned because the rail system often jams, causing the trigger to be stuck even for large squeezing forces.

<u>Test Three:</u> 

**Part:** Jaw-Trigger-String connection  
**What it is Testing:** Effectiveness of the assembly at opening the jaw wide enough.   
**How to Perform Test:** Using the assembled prototype, pull the trigger as far as possible and measure the opening distance of the jaw. Then, compare this height with the average size of an SLF egg mass.   

*Test Results:*   
- Measured opening distance: 1.95 inches
- Measured rest length opening: 1.05 inches
- Egg masses are roughly 1.5 inches long. (3)  

**Conclusion for Next Iteration:** We need to increase the amount the trigger pulls the lid upwards. The hinge and design allows the distance needed but the trigger is not currently able to pull it anywhere close to its maximum height. Due to limitations in the range of motion of a human hand, it will likely need to be redesigned to amplify the motion of a typical person's range of motion in their hand.

*Note:* We had initially planned a fourth test for the spring force of the bucket divider, but even before implementing, we could tell that the springs we ordered from McMaster would have too high a spring constant to be used and were too large, so we decided not to implement the divider until we had found the correct springs, which allowed us more time to focus on getting the complex jaw and bucket mechanism correct.

### Success Criteria
Our project is a prototype jaw device designed to remove spotted lanternfly egg masses from a variety of surfaces efficiently and safely. The goal is to improve egg mass removal efficiency and collection ability while being easy to operate.

<u>Criteria:</u>

- The final prototype should have high removal effectiveness such that after one use on a simulated Play-Doh “egg mass” on a variety of test surfaces (bark, metal, etc.) the remaining egg mass should be less than 10% of its original area. Using calipers in the TDS this can be measured repeatedly to observe average performance. Less than 10% remaining egg mass is a high priority.
- The final prototype should be durable such that after 100 cycles the jaw opening distance and clamping force remain with +/-5% of their initial measurements. The opening distance can be measured using a ruler and the clamping force can be measured using a spring scale. A higher durability tolerance than 5% after 100 cycles is mid priority.
- The final prototype should have a large jaw output force capable of scraping off an egg mass. The device should generate greater than or equal to 10N clamping force at the teeth on the jaw. This can be measured using a spring scale. More force is not a priority.
- The final prototype should be user-friendly such that it can be used for a long time, in many different angles and orientations, by many different people. The device should have a total score below 5 on the RULA (Rapid Upper Limb Assessment) and weigh less than 15 pounds. A lower RULA score and more usable orientations is high priority.

<u>Exhibit-Day Criterion:</u>
We think we will demonstrate removal effectiveness with an interactive exhibit. Visitors can use the device to try to remove Play-Doh “egg masses” from the test surface, which will be bark, metal, or plastic, and can then measure the material of the remaining egg mass. This will show effectiveness of the jaw for removing egg masses and minimal damage to the surface.

### References

1. Hedge, Alan. CUergo: RULA. Cornell University, <https://ergo.human.cornell.edu/ahRULA.html>. Accessed 23 Mar. 2026.

2. Ergonomics Plus: A Step-by-Step Guide: Rapid Upper Limb Assessment (RULA), <https://ergo-plus.com/wp-content/uploads/RULA-A-Step-by-Step-Guide1.pdf>. Accessed 23 Mar. 2026.

3. University of Rhode Island Biocontrol Lab. Biocontrol of Insects: Spotted Lanternfly: Identification and Life Cycle, <https://web.uri.edu/biocontrol/projects/slf-identification-and-life-cycle/>. Accessed 23 Mar. 2026.

