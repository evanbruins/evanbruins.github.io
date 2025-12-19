---
layout: page
title: Accurate FEA of fixed Beam Testing
description: George Fox 2024
img: assets/img/6.1.jpg
importance: 2
category: school
---

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

I conducted a structural study of fixed 3D printed beams under load, combining lab experiments with SolidWorks simulations to assess how geometry affects deflection and stress.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/6.5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Using a standard beam as a control, we measured its elastic modulus and incorporated it into simulations. Validation included consistent boundary conditions, mesh convergence, and quality metrics, yielding errors under 2% and confirming the modulus accuracy.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/6.4 copy.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We also tested L-shaped, T-shaped, and other geometrically modified beams. Larger deviations arose from internal cooling stresses and localized stiffness changes, showing the sensitivity of FDM printed materials to geometry.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/6.6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The study confirmed that accurate modeling of 3D printed beams requires careful correlation of physical testing and simulation. Among all variants, the straight variant beam performed best, showing the most consistent behavior and closest agreement between experimental and simulated results.