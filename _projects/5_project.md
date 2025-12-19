---
layout: page
title: FEA of a 3D printed AFO
description: George Fox 2024
img: assets/img/5.1.jpg
importance: 3
category: school
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/5.4 copy.jpg" title="anke-foot orthosis (AFO)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>

I collaborated in a two person team to perform a finite element sensitivity analysis on a 3D printed ankle–foot orthosis (AFO), using experimental stiffness measurements from a physical prototype as a baseline. The goal was to evaluate how modeling choices affect predicted deformation and stress.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/5.3.jpg" title="anke-foot orthosis (AFO)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption">
    Shell Mesh with initial fixation method
</div>

Shell mesh models, representing thin walled geometry, required 179 N to reach a 50 mm deflection. They were efficient but produced higher localized stresses, showing sensitivity to thickness and boundary conditions.

<div class="row mt-5">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/5.5.jpg" title="anke-foot orthosis (AFO)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption">
    Solid Mesh with final fixation method
</div>

Solid mesh models predicted 131.56 N for the same deflection and captured 3D stress behavior more accurately. Material properties were adjusted for moisture dependent nylon stiffness, including an 18% reduction in modulus and consideration of nonlinear behavior.

Mesh type and boundary conditions strongly influenced predicted behavior. Moisture adjusted material properties, careful constraint definition, and mesh convergence checks were key to improving finite element simulations for polymer orthopedic devices.

<div class="row justify-content-sm-center mt-5">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.6.jpg" title="Experimental Data" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.2.jpg" title="Model Render" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Experimental data and model render
</div>
