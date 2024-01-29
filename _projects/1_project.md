---
layout: page
title: To charge or not to charge, this is a question
description: Comparison of two parallel hybrid-electric architectures.
img: assets/img/proj_1/hybrid_structure.jpg
importance: 1
category: Electric Aircraft
---

For Hybrid-Electric Aircraft, it is generally assumed that the gas turbine and electric motor are connected mechanically, allowing the gas turbine to charge the battery during flight. The potential benefits includes: (a)The engine can run in its most efficient region to conserve fuel by using the electric motor as an extra load; (b)The electric motor can work in "one-engine-inoperative" (OEI) mode by charging the battery to its fully charged state after the climbing phase. These benefits are suitable for series, parallel, and series-parallel configurations.

However, these benefits have never been testified theoretically nor experimentally. 

We compare two parallel hybrid electric architectures-one with and one without mechanical connection between the engines and the electric motors-we apply the power allocation algorithm we proposed previously to the energy management for the propulsion system in a 19-seat conceptual Hybrid Electric Aircraft.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_1/ParallelHybrid.drawio.png" title="Connected parallel hybrid structure" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_1/independent parallel.drawio.png" title="Independent parallel hybrid structure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

After implementing the power allocation algorithm to this 19-seat aircraft, both theoretical and simulation results show that the fuel saving from charging the battery in-flight is negligible. For the other potential advantage of using the electrical path as a backup in case the engine fails, the simulation results show that with the same requirement
on the remaining battery charge, increasing battery pack capacity onboard is more fuel efficient than charging the battery during the flight. 

As such, the connected architecture does not bring significant fuel savings compared with the independent configuration. In addition, the mechanical connection increases
the system’s complexity and generally requires sophisticated control strategies. This architecture also makes it difficult to transition to an all-electric aircraft configuration. Lastly, charging the battery in a harsh flight environment requires an accurate thermal management system as well as causing battery degradation.

<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[hybchr=true]* %}
</div>

