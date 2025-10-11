---
layout: post
title: Line Following Robot
description: 🤖 Built a nimble, lightweight line-following robot with PID motor control for racing
skills: 
- Python
- C
- SolidWorks
- PID Motor Control
- Embedded Systems
- Rapid Prototyping
- Raspberry Pi
main-image: /robotside.jpeg
---
# 🚦 Project Highlights  
* Autonomous line-following differential drive robot** built for the 2025 Tech Cup in Northwestern’s Advanced Mechatronics course  
* Designed and fabricated a lightweight chassis using a mix of 3D printing and laser-cut parts; integrated supplied TT motors and battery pack for fair competition
* Tuned a PID control algorithm with nested current + position loops for smooth, fast lap performance
* Used a simple low resolution camera (OV7670) to detect robot's position on track on a white-line-on-purple-background track
* Balanced **speed, stability, and reliability** through iterative prototyping, CAD modeling, and real-world testing 

{% include image-gallery.html images="robotCAD.png" height="400" %}

### Control Algorithm
- **Line Detection**: Camera captures images in 640x480 pixel resolution at 30 fps. Then, an algorithm detects the white line on purple background and outputs an integer to calculate error.  
- **PID Control**: Adjusts motor speeds proportionally to the error between the robot’s position and the center of the line.  
- **Differential Drive**: Left and right motors are independently controlled for smooth turning.

{% include image-gallery.html images="robotiso.jpeg, cameratr2.png" height="400" %}
<br>
