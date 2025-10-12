---
layout: post
title: Injection Mold Design & Manufacturing
description: 👾 Designed a toy and a injection molding mass manufacturing process
skills: 
- Siemens NX
- CAM
- CNC
- Injection Molding
- Mold Design
- Mass Manufacturing
main-image: /among.jpeg
---

# Plastic Injection Molded Product (Among Us Character)
## Part & Accessory Design

**Problem**  
Design a customizable injection-molded character with attachable accessories while ensuring manufacturability and proper fit.

{% include image-gallery.html images="sketch.png" height="400" %}

**Solution**  
Created CAD models of the body, hat, and mustache with uniform wall thickness, draft angles, fillets, and an interference-fit pin system. Used a half-pin design to lock the front and back halves together and support accessories.

{% include image-gallery.html images="cad1.png, cad2.png" height="400" %}

**Results**  
- Functional interchangeable accessories  
- Stable, seamless assembly  
- Manufacturable geometry with minimal defects  


## Mold Design

**Problem**  
Design molds that allow clean parting lines, easy ejection, balanced flow, and controlled shrinkage.

{% include image-gallery.html images="mold1.png" height="600" %}

**Solution**  
Selected optimal parting lines, applied draft angles and fillets, maintained uniform thickness, and designed balanced runner systems with cold slug wells. Ensured spacing from mold walls to prevent flash.

{% include image-gallery.html images="runner.png, partingline.png" height="300" %}

**Results**  
- Smooth ejection  
- Minimal post-processing  
- Consistent cavity filling  


## CAM Programming & CNC Machining

**Problem**  
Accurately machine complex mold geometry with good surface finish and precise press-fit features.

**Solution**  
Created toolpaths for roughing, semi-finishing, and finishing using flat, ball, and tapered end mills. Spot drilled, drilled, and reamed holes for precision fits. Troubleshot shutoff size and hole depth issues manually.

{% include image-gallery.html images="cnc.png" height="400" %}

**Results**  
- Accurate press-fit dimensions  
- High-quality surface finish after light sanding  
- Fully machined molds ready for molding  


## Injection Molding Process Optimization

**Problem**  
Initial molding runs caused short shots, flashing, and uneven fill between parts.

**Solution**  
Iteratively adjusted pressure, temperature, and injection time for each mold pair to balance fill and prevent defects.

**Results**  
- Fully filled parts  
- Repeatable, reliable process parameters  
- Correct fits at critical features  

## Metrology & Quality Validation

**Problem**  
Verify dimensional accuracy and diagnose shrinkage or mold errors.

{% include image-gallery.html images="histogram.png" height="400" %}

**Solution**  
Measured key dimensions across 20 samples, compared to CAD specs, and analyzed deviations and trends.

**Results**  
- ~1–4% uniform shrinkage (expected for polypropylene)  
- Stable and normally distributed measurements  
- All parts fit and assembled correctly  


## Final Outcome
**Problem**  
Produce a fully functional, manufacturable, and customizable plastic product with minimal defects.

{% include image-gallery.html images="among.jpeg" height="400" %}

**Solution**  
Completed full pipeline: design, mold creation, CAM, machining, process tuning, molding, and inspection.

**Results**  
- Fully functional product with attachable accessories  
- Smooth assembly and reliable fit  
- Hands-on experience in CAD, CAM, CNC, molding, and QA  
- Identified future improvements (runner optimization, more draft, ejector pins, standardized tooling)
