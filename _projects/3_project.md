---
layout: page
title: Trajectory optimization for All-Electric Aircraft
description: 
img: assets/img/proj_3/All_Electric_aircraft.png
importance: 3
category: work
---

We formulate the operating cost minimization as an optimal control problem. The battery dynamics and flight dynamics are combined together, and the OCP is examined in the context of Pontryagin’s Minimum Principle
(PMP), providing necessary optimality conditions for the proposed integrated approach.

Battery models with distinct fidelities

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_3/ECM.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_3/BatterySchematic.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the Empirical Circuit Model. On the right, The Single Particle Model.
</div>

Optimal trajectory for a complete flight profile (climb-cruise-descent)