---
layout: page
title: Bungee Jumper Multibody Dynamics Simulation
description: George Fox 2024
img: assets/img/2.1.webp
importance: 2
category: school
giscus_comments: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.2.jpg" title="i-j-k Plane Position of Jumper" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.3.jpg" title="Angular Velocity of the Jumper" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.4.jpg" title="Cord Force" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <div>Left: i-j-k Plane Position of Jumper</div>
    <div>Middle: Angular Velocity of the Jumper</div>
    <div>Right: Cord Force</div>
</div>

I collaborated with a four person engineering team to develop a high fidelity multibody dynamics model of a human bungee jumping system. We derived and simulated the full nonlinear equations of motion governing three dimensional translation, rotation, and cord interaction using Newton–Euler formulations in coupled inertial and body-fixed frames. The resulting 15 state nonlinear ODE system was solved via a fourth order Runge–Kutta scheme, with logic to capture transitions between freefall and elastic extension. Parametric and sensitivity studies over cord stiffness, unstretched length, and initial conditions identified configurations that constrained displacement, sway, and forces within safety limits, yielding a validated framework for evaluating commercial bungee jump performance.


