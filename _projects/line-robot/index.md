---
layout: post
title: Line Following Robot
description: 🤖 Built a nimble, lightweight line-following robot with tuned PID control for racing
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
* Built an autonomous differential-drive robot to complete a 40-foot white-line track.
* Designed lightweight chassis with laser-cut & 3D printed parts.
* Tuned a PID control algorithm with nested current + position loops for smooth, fast lap performance.
* Used a simple low resolution camera (OV7670) to detect robot's position on track

### Control Algorithm
- **Line Detection**: Reads reflectance sensor values to detect the white line on purple background.  
- **PID Control**: Adjusts motor speeds proportionally to the error between the robot’s position and the center of the line.  
- **Differential Drive**: Left and right motors are independently controlled for smooth turning.

{% include image-gallery.html images="robotCAD.png, robotiso.jpeg" height="400" %}
<br>
