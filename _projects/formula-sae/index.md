---
layout: post
title: Northwestern Formula Racing Projects
description: I was in Northwestern Formula Racing for two years where I worked in the chassis and suspension teams. My main responsibilities were the rear hubs and the pedalbox.
skills: 
- SolidWorks
- DFM
- CNC Programming & Machining
- Finite Elements Analysis
- Topology Optimization
main-image: /MeNFR24.png
---
## Rear Hubs
I redesigned and coordinated the machining of the rear hubs, center locking nuts, and hubcaps for NFR 25. The hubs rigidly connect to the wheel assembly and allow the wheels to rotate with minimal friction, in conjunction with the uprights. They also serve as a mounting point for brake rotors via the use of float pins; especially, the rear hubs also transmit the driving force from the engine through the half-shafts into the wheels. The center locking nut constrains the axial motion of the wheel assembly within the upright.
### Design Goals:
* Accommodate transmitted forces during cornering, braking, and acceleration
* Reduce shear
* Optimize hub dimensions to minimize overall weight
I ran calculations to determine the critical stresses that the hubs are going to take and included a bump factor. Using these calculations, I ran FEA to minimize the weight of the hubs while keeping the factor of safety above 1.5.

{% include image-gallery.html images="HUBS.png, hubfea1.png" height="300" %}

After the design was complete, I created an engineering drawing and coordinated with a CNC machine shop to get the parts made and with another supplier to get the aluminum coated for regulations.

{% include image-gallery.html images="HubsDrawing.png, newhubs.png, BrakeRotor4.jpg" height="250" %}

Ultimately, achieved 6% weight reduction and 17% cost savings while maintaining a factor of safety greater than 1.5.

---

## Pedalbox
I designed and manufactured a pedal box consisting of a baseplate, gas pedal, brake pedal, throttle return springs, brake over-travel switch, and throttle sensors to accommodate the change from an ICE car to an EV. The pedal box is responsible for the car's braking and acceleration. It is adjustable for different heights through pedal rails. Also, the pedal box houses the killswitch, which turns off the car if the brakes fail and the pressure in the master cylinders drops.
### Design Goals:
* Accommodate transmitted forces during cornering, braking, and acceleration
* Return to 0% Pedal Travel when not pushed
* Shut down the car if the brakes fail
* Minimize weight
Ran FEA and topology studies to safely remove as much material from the pedals and the baseplate as possible.

{% include image-gallery.html images="pedalfea.png, image.png" height="400" %}

After the design was complete, I CNC'ed the pedals and the baseplate. I used the lathe to make the throttle shaft and then put together the pedalbox module and assembled it to the car.

{% include image-gallery.html images="Pedalbox.png" height="400" %}

Achieved precise throttle control and a reliable, safe pedalbox for the competition.
<br>
