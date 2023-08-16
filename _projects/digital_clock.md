---
layout: page
title: Digital Clock Enclosure
description: an enclosure for a digital clock made using an arduino
img: assets/img/dig_clock/Screen Shot 2022-03-16 at 9.17.33 AM.png
importance: 2
category: personal
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/IMG_0366.PNG " class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Clock in 24 HR Format based on Cupertino Time
</div>

<hr>

I wanted to create a digital clock with my friends. I was the
mechanical lead and the other two were mainly responsible for software
and electronics.

Originally, I planned on making a cube that would enclose the
arduino, breadboard and display.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/Capture.PNG" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/Capture2.PNG" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Brainstorm Sketches
</div>

<hr>

I knew I wanted to use screws to secure the top and bottom of the
enclosure. I fiddled around with different thread diameters and hole
sizes until I found one that worked for M3 screws that created tapped
holes in FDM 3D Printing. In order to save material, I slimmed down the
design and only kept what was necessary.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/old%20clock%20iso.PNG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/old%20clock%20top.PNG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    First Design
</div>

<hr>

When I designed the enclosure, I neglected to account for the size of
the plug for the power jack. I also had the display slot at the
incorrect height and I didn't leave enough space for wiring.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/IMG_0347.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    No room for power jack
</div>

<hr>

I reduced the shell thickness to 3mm because the 5mm thickness was
necessary, increased the length of the base, and moved the arduino mount
to the side to make room for the power jack. The documentation can be
viewed <a href="https://docs.google.com/document/d/1kIadXHNAuBpPpovvylge_1iNMiGNkolVfwdHakJqiZ0/edit">here</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/Screen%20Shot%202022-03-16%20at%209.17.33%20AM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/dig_clock/clock%20top.PNG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Final Design
</div>