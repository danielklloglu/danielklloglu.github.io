---
layout: post
title: Robot End Affector Additive Manufacturing
description: 🦾 Designed and iterated a lightweight PA12 3D-printed robotic end effector that securely grips and transports a fragile egg while minimizing material and maintaining structural integrity
skills: 
- Siemens NX
- Design for Additive Manufacturing
- SLS 3D Printing
- Finite Elements Analysis
- Topology Optimization
main-image: /RobotEndEffectors.jpg
---
## Robot End Effector – Lightweight PA12 Egg Gripper

**Problem**  
Design a 3D-printed end effector capable of securely gripping and moving a fragile egg without breaking it, while minimizing weight to improve robot arm efficiency. The design also needed to withstand force/deflection testing, integrate with solenoids, and mount to the robot using a dovetail connector.

{% include image-gallery.html images="endfea.png, testing.png" height="400" %}

**Solution**  
We used **Polyamide 12 (PA12) via SLS 3D printing** and went through **two major design iterations** to optimize strength, weight, and functionality:

- Identified bolts as the largest weight contributor and minimized bolt length.
- Nested the moving effector inside the static effector to reduce material and allow smaller hardware.
- Iteration 1: Thick, safe design that passed static tests but exceeded force limits on the moving part.
- Iteration 2: Aggressively reduced material using FEA and topology-style optimization while keeping a safety factor.
- Added trusses and edge blends to improve bending resistance.
- Tuned the cusp shape to enhance egg stability and tolerance.
- Accounted for PA12 variability in strength and deflection between FEA and real testing due to SLS build orientation and wall thickness differences.

{% include image-gallery.html images="RobotEndEffectors.jpg, finalrig.png" height="400" %}

**Results**  
- Successfully moved the egg during final robot test
- Lightweight, material-efficient final design 
- Stable grip from nested alignment and cusp support  
- Passed force/deflection tests with acceptable safety factor  
- Demonstrated effective balance of strength, precision, and weight using PA12  
<br>
