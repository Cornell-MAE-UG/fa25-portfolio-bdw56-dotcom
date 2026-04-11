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

## Functional Prototype
![Initial Drawing]({{ "/assets/images/Table1pt1.png" | relative_url }}){: width="575px"}


### Design Intent and Functionality:   
    We used the calculations and design estimates from our proof of concept and the feedback we received to refine our design and build our functional prototype. 
	Our bucket and jaw assembly, made out of lightweight 3D-printed plastic, is designed to hold 100 egg masses. For our first prototype, we decided to use PLA because it is cost-effective and the RPL can print it quickly. We designed the bucket to have an angled opening and curved bottom, so it works at different angles. The springs attach to the inside of the bucket and jaw, and the assembly moves with the help of the hinge and string on top.

<div style="display: flex; gap: 20px; text-align: center;">

<div>
  ![Figure 1]({{ '/assets/images/Figure 1.png' | relative_url }})
  **Figure 1:** Bucket and Jaw Side View Closed
</div>

<div>
  ![Figure 2]({{ '/assets/images/Figure 2.png' | relative_url }})
  **Figure 2:** Bucket and Jaw Side View Open
</div>

</div>

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

