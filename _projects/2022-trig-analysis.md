---
layout: project
title: Heat Exchanger Analysis
description: Class project with Schematics
technologies: [GoodNotes, GoogleDrawings]
image: /assets/images/overall-heat-exahnger.jpeg
---
## Heat Exchanger Lab Overview
My thermodyanmics class setup a lab where we could examine how the initial temperatures of a hot bath and cold bath of water would change after running through a heat exchanger -- a device that takes in two liquids seperated by a solid barrier and exchanges the heat between the two either with parallel flow or counter flow. To best show this device, my group tested putting the liquids flowing through the heat exchanger in parallel (and + / - pump speed) along with in counter-flow (and + / - pump speed) in order to come to a conclusion of which is more efficient (including pump speed). To best represent this, the diagram below shows a schematic of the heat exchanger with its control volume boundary around the heat exchanger. To be in parallel flow, either the liquid flows from 1 -> 2 and the other flows from 3 -> 4 or vise versa. For counter-flow, either the liquid flows from 1 -> 2 and the other flows from 4 -> 3 or the liquid flows from 2 -> 1 while the other flows from 3 -> 4. (The first picture shows parallel flow and the second shows counterflow).

![Photo of diagram]({{ "/assets/images/Heat Exchanger Drawing.jpg" | relative_url }})

<div class="image-row">
  ![Parallel flow]({{ "/assets/images/parallel-flow.jpeg" | relative_url }})
  ![Counter flow]({{ "/assets/images/counter-flow.jpeg" | relative_url }})
</div>

## Data
Assuming this is an ideal heat exchanger, it does no work (as the pumps inside of the hot and cold water baths are the ones doing the work). This means the heat is exchanged between the hot and cold inside of the heat exchanger by taking heat from the hot flow and into the cold flow. Here is the equation I used to find change in enthalpy and any excess heat that was probably taken up by material of the heat exchanger itself as there was a temperature change of the outsides of the heat exhchanger.

![Photo of control volume explanation]({{ "/assets/images/CV-explanation.jpeg" | relative_url }})

![Photo of data]({{ "/assets/images/Heat-exchanger-data.jpeg" | relative_url }})

## Analysis

Due to the Qnet not equaling 0, this heat exchanger is not perfect; however that is expected. Although it is not a lot of energy (although it could be more or less for each because I used made up mass flow rates for + / - flow), there is still some net positive enegry that was absorbed by the heat exchanger. This means that the device itself is not fully adiabatic. This can also be seen through data as the border temperature of the heat exchanger on both the cold flow side and the hot flow side increased before and after pumping the water.

When comparing the most ideal situations however, if the change in temperature of the water was to be the same, then no energy was absorbed by the border of the heat exchanger and eventually leaving the device to outside the system thus making it the "best" (yet would still generate entropy - nonreversible - as there is heat exchange over a finite change in temperature). As seen from the data above, the closest points where the magnitudes of the cold and hot temperature changes being the same was counterflow with negative pump speed while the farthest away was counterflow with positive pump speed. Theoertically, this makes sense since with a lower pump speed, the heat transfer can act more quasi-statically than if it was faster (a slower pump allows the water to reach closer to equilibrium every second before pumping more water through the heat exchanger). 

Comparing efficiencies shows which type of flow leads to a more ideal situation where the change in temeperature of a bath is equal to the temperature difference between the hot bath and cold bath. Using the values above, the efficiencies (shown in the data table), show how counterflow is 30–60% more effective than parallel flow. Also looking at the data, only counterflow allows the cold outlet temperature to exceed the hot outlet temperature.

This makes physichal sense because parallel flow suffers from rapid temperature equalization near the inlet, limiting heat transfer. In other words, the total amount of heat that can be transferred is constrained because the driving force for heat transfer, the temperature difference, drops quickly in the beginning leading to the fluids being "unable" to exchange as much heat over the length of the heat exchanger. This leads to the smaller efficincies when compared to counterflow where their lies large temperature differences between both ends of the heat exchanger allowing for a larger average magnitude of heat to transfer between the solid border inner-walls.

## Conclusion
Although a true heat exchanger efficiency cannot be calculated without mass flow rates, a relative effectiveness comparison was performed using inlet and outlet temperatures of hot and cold baths of water. Counterflow operation exhibited significantly higher effectiveness than parallel flow, with the highest effectiveness occurring at lower pump speeds due to increased time for quasi-static heat exchange.

## Sources of Error
To make this better and closer to ideal results, first I would do many more tests to gain a higher understanding of what this heat exhanger's results tend to. Also, I would use a pump that pumps water more slowly to act more quasi-statically (as stated above). I would also make sure the hot bath and cold bath are at higher and lower temperatrures, respectively, since this will lead to a better understanding of how the heat from one bath goes through the control volume heat exchanger and out into the empty bath.

Steady state was assumed but this could not be entirely true. To optimize steady state, the kinks out of the tube so that the water flow could flow smoothly and at the speed of the aquatic pump. However, since one pump was used inside the hot bath and another in the cold bath, the rates at which the water flowed through the heat exchanger could be slightly different. This would mean that m_in does not equal m_out and therefore, not exactly steady-state.

By using some sort of insulated container to place the heat exchanger inside, a greater interpretaion on the idealized, adiabatic heat exchanger could be examined as Qnet would be lower due to the smaller decrease of heat escape from the control system and therefore a larger temperature change between the two baths (less heat goes out of the heat exchanger and is instead exchnaged between the hot and cold water).