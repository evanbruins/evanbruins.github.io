---
layout: page
title: FEA of a 3D printed AFO
description: George Fox 2024
img: assets/img/5.4.jpg
importance: 3
category: school
---

{% include figure.liquid path="assets/img/5.1.jpg" title="AFO FEA - result 1" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/5.2.jpg" title="AFO FEA - result 2" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/5.3.jpg" title="AFO FEA - mesh comparison" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/5.4.jpg" title="AFO FEA - deformation" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/5.5.jpg" title="AFO FEA - stress plot" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/5.6.jpg" title="AFO FEA - experimental setup" class="img-fluid rounded z-depth-1" %}

I collaborated with a two-person engineering team in carrying out a finite element sensitivity analysis on a 3D-printed ankle–foot orthosis using experimental stiffness measurements from a physical prototype as our performance baseline. We developed several SolidWorks Simulation models that varied material properties, mesh types, and fixation constraints to understand how each modeling assumption influences predicted deformation and stress behavior. Because the nylon material used in the AFO exhibited moisture-dependent stiffness and nonlinear behavior, we incorporated an 18% reduced modulus of elasticity and reviewed hyperelastic material characteristics to better align the simulations with real-world mechanical response.
We found large variations in the predicted force–deflection behavior across solid and shell mesh formulations: solid mesh requires 131.56 N to reach a deflection of 50 mm, while shell mesh requires 179 N to reach the same deflection but resulted in higher localized stresses. The selection of boundary conditions was one of the most influential factors in model output, especially due to the differences introduced by arch, heel, and toe mounting. This study identified careful constraint definition, moisture-adjusted material modeling, and checks for mesh convergence as important considerations when analyzing polymer orthopedic devices, providing a clearer path toward more accurate simulation-driven orthotic design.
