---
layout: page
title: Autonomous Race Car
description: using python OpenCV to drive a race car autonomously
img: assets/img/auto_car/Screen Shot 2022-12-07 at 11.26.41 AM.png
importance: 1
category: class
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/auto_car/Screen Shot 2022-12-07 at 11.31.03 AM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    3D Model of Electronics Mounts
</div>

<hr>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/auto_car/Screen Shot 2022-12-07 at 11.30.23 AM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example Code in Main
</div>

I worked on developing the code for the race car to drive autonomously. I experimented with two different methods: lane detection and line following. 

lane detection method: the camera would detect the left and right lanes and drive in the direction of the average

line following method: the camera would detect the yellow centerline and follow that line.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/auto_car/Screen_Shot_2022-11-23_at_10.01.40_PM.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/auto_car/Screen Shot 2022-12-07 at 11.33.17 AM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Lane detection (left) and centerline following (right)
</div>

The repository can be found here at <a href="https://github.com/rqnguyen100/MAE_148_Team8_OpenCV">https://github.com/rqnguyen100/MAE_148_Team8_OpenCV</a> and the video can be found here: <a href="https://youtu.be/YZXyHBGTka8">youtube link</a>