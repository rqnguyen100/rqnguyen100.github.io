---
layout: page
title: NASA L'SPACE Mission Concept Academy
description: a rover capable of traversing a Martian cave and accomplishing specific science objectives
img: assets/img/MCA/Screen Shot 2022-08-06 at 3.34.08 PM.png
importance: 1
category: academy
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.34.08 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.34.18 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Isometric and side view of proposed rover CAD model
</div>

<hr>

The full mission task can be viewed <a href="https://drive.google.com/file/d/1-ALkocUUJLu3coLEQA0IzYUTy9EY-R1N/view?usp=sharing">here</a>. In essence, the task is to create science objectives to accomplish while searching inside a Martian cave and the proposed solution to traverse the cave and complete these science objectives.

At the beginning, a list of requirements and constaints was created to understand what the team, which included both science and engineering students, was restricted by and had to accomplish.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.32.07 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    System, functional, and performance requirements
</div>

<hr>

As a mechanical engineer, my task was to work on the design of the rover and how it will be implemented with other sub-systems. I created a trade study to determine the best way to navigate inside of a cave. Wheels, ultimately, won due to the simplicity and heritage level. The main reason was that I decided exploring only 30-40% of the cave with a higher confidence level was better than using something experimental with a much higher exploration ability. 

I brainstormed some ideas for the robot. Due to the lack of controls, I
leaned heavily towards a robotic arm.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.33.27 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drive train trade study
</div>

Next, I made some sketches for the rover and was heavily inspired by Curiosity and Perseverance. Heritage level or TSL was extremely important for the project which also helped decide the drive train. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.33.39 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.33.51 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Sketches
</div>

<hr>

With the help of the lead systems engineering, I created a N^2 and system interfaces diagram to help showcase how the different systems in the rover would interface with one another. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.33.10 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.34.34 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    N^2 diagram (left) and System Interface Diagram (right)
</div>

I also worked on a Failure Mode and Effects Analysis (FMEA) chart and risk summary to help define what risks the rover and team would be dealing with and how to best mitigate these risks. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.38.20 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    FMEA Chart
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.38.46 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.38.56 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Risk Summary and Matrix
</div>

<hr>

While I did do some CAD for the rover, it was a minimal part as I worked on analysis instead and my colleagues worked on the majority of the CAD. The images at the top of the page showcase their work. 

Below are some of the general calculations, I did for the rover. The two below are to determine the minimum area needed for the tether to avoid tensile failure and the minimum area needed for a column to avoid both a buckling and bending moment failure. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.34.50 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.35.52 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Tether and mount analysis
</div>

<hr>

My largest contribution to the rover was performing a static analysis on the suspension system. I started with hand-calculations to determine the forces in each of the linkages and determined compressive and bending failures. My assumptions were very generous and can be seen in the verification step when I did a static simulation. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.36.42 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.36.47 PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Suspension frame hand-calculations.
</div>

<hr>

I utilized Ansys to perform a static structural analysis of the rover and used a draft model for simplicity. My boundary conditions were the following: the weight of the rover acting in the negative y-direction and fixed supports at the wheel axles. Even though the rover moves, I deemed it fine and called it a quasi-static analysis since it moves at a rate of 2 miles per hour. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.37.27 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.37.31 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Boundary Conditions
</div>

I was interested in the deformation of the rover to help verify the model was performing correctly and the von-Mises stress to determine if any part of the rover would fail.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.37.53 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.38.00 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Deformation and von-Mises stress plot
</div>

I experimented with the mesh sizings and plotted the number of nodes to see where it converges. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MCA/Screen Shot 2022-08-06 at 3.37.43 PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Mesh Convergence Plot
</div>

Due to the simplicity of the calculation and assumptions, the calculated value and simulated values were much different, on a scale of 100 times. This makes sense since my assumptions were conservative. When a final design of the rover was created, I also tried to import the model into Ansys and re-perform the simulation but was unable to do so due to the complexity of the model and the limitation of my license. 

<hr>

The end result of this project was the mission concept report and the preliminary design report detailing the entire mission. These reports and the presentation slides can be viewed in the documentation section of the website.