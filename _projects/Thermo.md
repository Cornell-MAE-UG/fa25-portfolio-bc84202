---
layout: project
title: Thermo Heat Exhcnager Lab
description: A lab in thermo where we analyzed a heat exchanger
image: /assets/images/Thermo-setup1.png
---

## Overview
In our Thermo class, we had a lab where we analyzed a small heat exchanger. This heat exchanger worked by taking in two flows and running them right next to each other while not allowing them to mix. The flows are split by metal, which acts as a heat conductor to allow heat to transfer. The heat exchanger also splits each flow up into multiple smaller flows as to maximize the surface area of the flow touching the metal, allowing more heat to transfer faster.

We had a hot resevoir and a cold resevoir of water, and we set up the heat exchanger so that we ran it twice with parallel flow, and twice with counter flow to compare and see which one is better.

## Setup
For the parallel flow, we set it up by connecting a pipe from the hot resevoir to an inlet of the heat exchanger, and another pipe from the outlet to a bin so we can measure the temperature afterwards. We did the same with the cold resevoir, using the same side for inlet as the hot resevoir's inlet and our setup looked like this:

![Shaded rendering of earlier version]({{ "/assets/images/Thermo-setup1.png" | relative_url }}){: .inline-image-r style="width: 200px"}

For counter flow, the setup was very similar, but the hot resevoir's inlet was on the other side(here it's the right side) so the fluids would flow in opposite directions.

![Shaded rendering of earlier version]({{ "/assets/images/Thermo-setup2.png" | relative_url }})

Note that the water from the hot resevoir was dyed with red food coloring and water from the cold resevoir was dyed with blue food coloring for clarity.

## Results
| Type         | Thi (°C)    | Tho (°C)     | Tci (°C)    | Tco (°C)     |
|--------------|-------------|--------------|-------------|--------------|
| Parallel-flow| 35.0        | 23.7         | 8.7         | 21.1         |
| Counter-flow | 35.0        | 18.4         | 7.5         | 23.1         |
Flow rate: 210 gallons/hour
## Analysis
<img src="/assets/images/Thermo-analysis.png"
     alt="aa"
     style="max-width: 100%; height: auto; display: block; margin: 0 auto;">

Using our data, we can see that for the parallel flow, Qdot=11.413952kJ when calculated with the cold flow and Qdot=10.401424kJ when calculated with the hot flow. These values are similar, but not exactly the same as predicted. This is likely due to some heat loss to the surrounding environment while the heat was still trasfering.

For the counter flow, Qdot=14.359488kJ when calculated with the cold flow and Qdot=15.279968kJ when calculated with the hot flow. We can see that once again the values were similar. For the counter flow, we can easily see that significantly more heat transfer was happening.

There is likely more heat transfering 