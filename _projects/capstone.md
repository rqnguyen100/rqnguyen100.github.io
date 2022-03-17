---
layout: page
title: Capstone Project
description: using a chain-link mechanism to reduce with and maintain torque and power efficiency
img: assets/img/capstone/Screen Shot 2022-03-16 at 9.35.45 AM.png
importance: 1
category: year 1
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/capstone/Screen%20Shot%202022-03-16%20at%209.18.16%20AM.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Initial vs. Final Turret Design
</div>

<hr>

My task was to reconfigure the turret pitch mechanism. Based on the
initial design, the current turret had a pitch mechanism that was
direct-drive (the motor is on the left), but it wasn't very space
efficient since the motor was just sticking out on the side. The goal
was to move the motor down and drive the pitch motion with a different
mechanism.

I started looking at the competition rules to find what constraints I
had when designing the new mechanism and also any important information
like the current weight of the turret and the motor information (rated
torque, speed range, etc). Those can be viewed <a href="https://drive.google.com/file/d/1P8NQhDhZxjAlpo5Sa__fYhyWBH9V3yDT/view">here</a>.

Next, I started doing calculations to understand what was the current
torque and power needed to pitch the turret, so I could get a sense of
how much torque and power efficiency I needed to stay within competition
rules. I documented them
<a href="https://docs.google.com/document/d/1e3-Q6rvSNrKmn3UQ8uPwbIetk7SKeuIns7weM6VrYak/edit">here</a>.

I started brainstorming rotary to rotary motion mechanisms. I first
looked into 4-bar parallelogram linkages since it was a simple
mechanism, but I was worried about how structurally stable it would be
and the possibility of the deadlocking when the linkages were parallel.
I then looked into belt drives, chain drives, and gear drives. I made a
pros and cons list and ultimately, I ended up deciding to use a chain
drive because of cost and that it would save the most space. The
distance between the driving and driven shaft was too far apart and
would result in using many gears. The mechanism would have to be
bidirectional so the turret could pitch forward and backward. I didn't
have any experience with belt drives and was worried that there would be
too much slack and it could only rotate in one direction. Throughout the
process, I also checked relative drive prices on MISUMI USA,
McMaster-Carr, and Amazon since price was a huge factor in determining
what mechanism to use. My list of pros and cons can be viewed <a href="https://drive.google.com/file/d/1F1mSBeniZmLwwmYNhdKYUykx8Le5ObbH/view">here</a>.

<hr>

#### Result
<li>Decreased the width of the turret by 5%</li>
<li>Maintaining a torque and power efficiency of about 98.49% assuming
    ideal conditions</li>
<li>Cost of changing the drive would be about $70</li>

The animation can be viewed
<a href="https://drive.google.com/file/d/1ziuBEdVXZrmUPWy-DRproZ-QHcZRSrKI/view">here</a>
and the project was documented
<a href="https://docs.google.com/document/d/1da-nxU-m3ClYu9xApHKVuSp-TNhM8wPkP42_-jZJcAE/edit">here</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/capstone/Drawing.PNG " class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drawing
</div>