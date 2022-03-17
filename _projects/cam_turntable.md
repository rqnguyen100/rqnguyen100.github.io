---
layout: page
title: CAM Programming
description: a fusion360 cam program to use on a CNC mill
img: assets/img/cam/turntable.PNG
importance: 3
category: year 2
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/cam/turntable.PNG "example image" title="example image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/cam/Screen%20Shot%202022-03-16%20at%202.48.59%20PM.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    PCAM Program on left and Turret Base (Turntable is purple and turntable
add-on is cyan) on right.
</div>

<hr>

A slew bearing or turntable is being used to help the turret of a robot
yaw. In order to mount the plates of the turret base, a "turntable
add-on" was created. Previously, a FDM 3D printed part was used. The
necessity of it being machine is to have tapped holes. Without tapped
holes, it would be difficult to fasten and un-fasten nuts. A CNC Program
was created using Fusion360's CAM software to achieve this.