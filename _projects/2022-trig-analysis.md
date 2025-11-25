---
layout: project
title: Heat Exchanger Analysis
description: Class project with Schematics
technologies: [GoodNotes, GoogleDrawings]
image: /assets/images/overall-heat-exahnger.jpeg
---

My thermodyanmics class setup a lab where we could how the initial temperatures of a hot bath and cold bath of water would change after running through a heat exchnager (the heat exchanger takes in two liquids and exchanges the heat between the two with a solid barrier between the two). To best show this result, my group tested putting the liquids flowing through the heat exchanger in parallel (and + / - pump speed) along with in counter-flow (and + / - pump speed). To best represent this, the diagram below shows a schematic of the heat exchanger with its control volume boundary around the heat exhcanher. To be in parallel flow, either the liquid flows from 1 -> 2 and the other flows from 3 -> 4 or vise versa. For counter-flow, either the liquid flows from 1 -> 2 and the other flows from 4 -> 3 or the liquid flows from 2 -> 1 while the other flows from 3 -> 4. (The first picture shows parallel flow and the second shows counterflow)

![Photo of diagram]({{ "/assets/images/Heat Exchanger Drawing.jpg" | relative_url }}){: .inline-image-l}

![Photo of parallel flow]({{ "/assets/images/parallel-flow.jpeg" | relative_url }}){: .inline-image-l}

![Photo of diagram]({{ "/assets/images/counter-flow.jpeg" | relative_url }}){: .inline-image-l}

Assuming this is an ideal heat exchanger, it does no work (as the pumps inside of the hot and cold water baths are the ones doing the work). This means the heat is exchanged between the hot and cold inside of the heat exchanger by taking heat from the hot flow and into the cold flow. Here is the equation I used to find change in enthalpy and any excess heat that was probably taken up by material of the heat exchanger itself as there was a temperature change of the outsides of the heat exhchanger.

![Photo of control volume explanation]({{ "/assets/images/CV-explanation.jpg" | relative_url }}){: .inline-image-l}

![Photo of data]({{ "/assets/images/Heat-exchanger-data.jpeg" | relative_url }}){: .inline-image-l}

Seen from those pictures, due to the Qnet not equaling 0, this heat exchanger is not perfect; however that is expected. Although it is not a lot of energy, there is still some net positive enegry that was absorbed by the heat exchanger.

When comparing the most ideal situations, if the change in temeprature of the water was to be the same, then no energy was absorbed by the heat exchanger thus making it the "best." As seen from the data above, the closest to the magnitudes of the tmeperatures being the same was counterflow with negative pump speed while the farthest away was counterflow with positive pump speed. Theoertically, this makes sense since with a lower pump speed, the heat transfer can act more quasistaclly than if it was faster (it can't go to equilibirum every second before pumping more water through the heat exchanger). 

To make this better and closer to ideal results, first I would do many more tests to figure gain a higher understanding of what this het exhanger's results tend to. Also, I would use a pump that pumps water more slowly to act more quasistacally (as stated above). I would also make sure the hot bath and cold bath are higher and lower temperatrures, respectively, since this will lead to a better understanding of how the heat from one bath goes through the control volume (heat exchanger) and out into the empty bath.
