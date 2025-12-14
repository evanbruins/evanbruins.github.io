---
layout: page
title: Accurate FEA of fixed Beam Testing
description: George Fox 2024
img: assets/img/6.1.jpg
importance: 2
category: school
---

{% include figure.liquid path="assets/img/6.1.jpg" title="Fixed beam - test 1" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/6.2.jpg" title="Fixed beam - test 2" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/6.3.jpg" title="Fixed beam - mesh" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/6.4.jpg" title="Fixed beam - comparison" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/6.5.jpg" title="Fixed beam - deflection" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/6.6.jpg" title="Fixed beam - setup" class="img-fluid rounded z-depth-1" %}

I performed a structural verification study to accurately model fixed 3D-printed beams under load, using controlled laboratory experiments coupled with SolidWorks static simulations. The test setup I designed with my teammate tested deflection behavior across multiple beam geometries, including straight, L-shaped, and T-shaped variants, using a standard, unmodified beam as the control specimen. We experimentally found the elastic modulus of the control beam and brought that value into our simulation environment, allowing high-fidelity comparison between the analytical predictions and measured performance.
Specific steps we took to validate the accuracy of the simulation include consistent boundary conditions, a mesh convergence study, and quality metrics including aspect ratio thresholds that ensure the robustness of the mesh. These results showed errors of less than 2% for the control beam, which confirmed that our experimentally derived modulus was accurate, while larger deviations in the geometric variations within the notched beams were due to internal cooling stresses and localized changes in stiffness. This study underlined the sensitivity of FDM-printed materials to geometry-dependent material behavior and proved the necessity of thorough model refinement during the correlation of physical testing and finite element analysis.