---
layout: page
title: Brayton Cycle Engine Design
description: George Fox 2023
img: assets/img/4.1.jpg
importance: 3
category: school
---

This project analyzed a T55-GA-5512 gas turbine engine modeled as an idealized Brayton cycle to evaluate design modifications for different performance goals. Using manufacturer data and EES, three cycle configurations were developed and compared: a stock baseline, a thermal efficiency optimized design, and a horsepower optimized design.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.2.jpg" title="Brayton study - chart 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.3.jpg" title="Brayton study - diagram 1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Stock schematic and T-s diagram
</div>

The stock cycle established baseline performance using assumed compressor and turbine isentropic efficiencies of 0.85 and a compression ratio of 8:1. This model provided reference values for thermal efficiency, net work, and heat transfer.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.4.jpg" title="Brayton study - chart 2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.5.jpg" title="Brayton study - diagram 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Efficiency Optimized schematic and T-s diagram
</div>

The efficiency optimized design added a regenerator to recover exhaust heat and reduce required heat input while maintaining constant horsepower. This configuration improved thermal efficiency and illustrated the benefits of waste heat recovery.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.6.jpg" title="Brayton study - chart 3" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/4.7.jpg" title="Brayton study - diagram 3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Horspower Optimized schematic and T-s diagram 
</div>

The horsepower optimized design incorporated a reheater and second turbine stage, with intermediate pressure adjusted to preserve baseline efficiency. This approach significantly increased power output and demonstrated staged expansion for power augmentation.

This study highlighted how Brayton cycle modifications can be tailored to specific efficiency or power goals, while reinforcing skills in thermodynamic modeling and engineering tradeoff analysis.