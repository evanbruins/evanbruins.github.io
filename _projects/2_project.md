---
layout: page
title: Bungee Jumper Multibody Dynamics Simulation
description: George Fox 2024
img: assets/img/2.1.webp
importance: 2
category: school
giscus_comments: false
---

{% include figure.liquid path="assets/img/2.2.jpg" title="Bungee simulation - visual 2" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/2.3.jpg" title="Bungee simulation - visual 3" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid path="assets/img/2.4.jpg" title="Bungee simulation - visual 4" class="img-fluid rounded z-depth-1" %}

In this project, I worked in an engineering team of four individuals to develop a high-fidelity multibody dynamics model of the human bungee-jumping system. The objective was to derive and then simulate the complete nonlinear equations of motion, which would describe a jumper's three-dimensional translation, rotation, and cord interaction. We developed the model by first using an inertial reference frame and a body-fixed frame linked via a ψ-θ-φ Euler rotation sequence, with a complete direction-cosine matrix whose elements were time-varying independent state variables. From free-body and kinetic diagrams, we developed coupled translational and rotational equations in Newton-Euler forms by defining the cord tension, linear and rotational aerodynamic drag, gravity, and angular momentum derivatives in the body frame.
These equations were implemented as a 15-state nonlinear ODE system and solved using a fourth-order Runge-Kutta integrator with a 0.1 s time step. The simulation dynamically handled transitions between freefall and elastic extension based on the unstretched cord length L₀ and real-time stretch magnitude. We performed parametric sweeps over spring stiffness k and L₀ to identify configurations that constrained maximum vertical displacement to 0.9h and lateral sway to less than 0.92w. Additional sensitivity studies quantified how initial linear velocity components, angular velocities, and jumper orientation influenced the overall trajectory. Numerical results indicated that the optimized system remained robust across realistic initial conditions, with cord forces staying well below material failure thresholds and human injury limits.
The project combined advanced rigid-body dynamics with nonlinear simulation, parameter optimization, and safety envelope analysis to generate a validated modeling framework suitable for the assessment of commercial bungee-jumping system performance.


