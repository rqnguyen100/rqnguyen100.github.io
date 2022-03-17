---
layout: page
title: Robotic Arm
description: the forearm of a 2 joint robotic arm
img: assets/img/robotic_arm/robo_arm_cad.png
importance: 1
category: class
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/robo_arm_cad.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/robo_arm_phy.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    CAD and Physical Model
</div>

<hr>

My group and I was tasked with creating a robot that was capable of picking up a 3 inch cube from various heights around the playing field and tranferring it to a central location. The rules can be viewed
<a href="https://drive.google.com/file/u/0/d/1sFnk3V-MtX1uIdrultbhL6gNIKYzWCXJ/view">here</a>.

I brainstormed some ideas for the robot. Due to the lack of controls, I
leaned heavily towards a robotic arm.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.25.35%20PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.25.23%20PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.25.59%20PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.25.23%20PM.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Concept sketches
</div>

<hr>

My role was to create the upper joint of a 2 joint robotic arm. I utilized a four-bar linkage mechanism to ensure the gripper was always parallel with the floor. A proof of concept was made to justify the design with cardboard.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.29.33%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.29.22%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Version <a href="https://docs.google.com/document/d/1nACYF_xE9qNAJEEBiZc-eNjEdMCn1mI8GcQKQosXUHE/edit">1</a> on the left and cardboard design on the right
</div>

<hr>

The problem with this design was that I chose the wrong axis of
rotation. I changed the axis of rotation and did calculations to
determine the amount of torque needed that can be viewed
<a href="https://drive.google.com/file/d/1auFzmpmmLdMOltGCYxQz5unbl5TLeu4w/view">here</a>. Our first prototype was built.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.32.35%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.32.55%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Version <a href="https://docs.google.com/document/d/1PNQWlg718dBlwFBqNWdTbRzIUyUubblIc8emvUYIfgY/edit">2</a> on the left and first complete design on the right
</div>

<hr>

I maximized the linkage lengths and did more hand calculations <a href="https://drive.google.com/file/d/1QtNHw0eXXiMpOrzTOZtGRHfQ7iFJsgnL/view">here</a>
to determine the amount of torque needed. Due to the sector gear, it
could not rotate 180 degrees. I also made both the linkages have gears
to distribute the load more evenly and added more teeth for a larger
range of motion.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.35.08%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/robotic_arm/Screen%20Shot%202022-03-16%20at%204.35.16%20PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Version <a href="https://docs.google.com/document/d/1tJsQTb9nn1cgjm6QuXs6B72u6EuHc_e5PYM-1KA_AbM/edit">3</a> on the left and version on the right version <a href="https://docs.google.com/document/d/1OOQ1Ngjj0I17WTjuLPNdzYWPhfDSPIMN8LyZ_gtX7fw/edit">4</a>.
</div>

<hr>

The <a href="https://drive.google.com/file/d/1j3MobIJ5YrzyseJnw3YjOh7sXieznqwn/view">final report</a>,
<a href="https://docs.google.com/presentation/d/1LGBYCD3udhznrWJmj9JKxS9Fy11l8CA_Yq4dBLMGI3o/present?slide=id.g8794a74c9d_0_2475">presentation</a>,
and
<a href="https://drive.google.com/file/d/1PdR_kffKF_dnmp_4I_LY9-6nX6uH3-pg/view">animation</a> are embedded here.