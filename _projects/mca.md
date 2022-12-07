---
layout: page
title: NASA L'SPACE Mission Concept Academy
description: a rover capable of traversing a Martian cave and accomplishing specific science objectives
img: assets/img/nasa/nasa logo.jpeg
importance: 1
category: other
---
#### Task
The task is to create science objectives to accomplish while searching inside a Martian cave and the proposed solution to traverse the cave and complete these science objectives.

<hr>

#### What I Did as a Mechanical Engineer
<li>worked on the design of the rover and how it will be implemented with other sub-systems</li>
<li>worked on a Failure Mode and Effects Analysis (FMEA) chart and risk summary to help define what risks the rover and team would be dealing with and how to best mitigate these risks. </li>

<hr>

#### Analysis and Simulation
<li>hand-calculations to determine the forces in each of the linkages and determined compressive and bending failures. My assumptions were very generous and can be seen in the verification step when I did a static simulation</li>
<li>utilized Ansys to perform a static structural analysis of the rover and used a draft model for simplicity. My boundary conditions were the following: the weight of the rover acting in the negative y-direction and fixed supports at the wheel axles. Even though the rover moves, I deemed it fine and called it a quasi-static analysis since it moves at a rate of 2 miles per hour. </li>
<li>experimented with the mesh sizings and plotted the number of nodes to see where it converges</li>
<li>interested in the deformation of the rover to help verify the model was performing correctly and the von-Mises stress to determine if any part of the rover would fail.</li>

<hr>

#### Result
Due to the simplicity of the calculation and assumptions, the calculated value and simulated values were much different, on a scale of 100 times. This makes sense since my assumptions were conservative. When a final design of the rover was created, I also tried to import the model into Ansys and re-perform the simulation but was unable to do so due to the complexity of the model and the limitation of my license. 

The end result of this project was the mission concept report and the preliminary design report detailing the entire mission. 