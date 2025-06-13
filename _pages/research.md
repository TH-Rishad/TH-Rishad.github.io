---
title: "Research"
layout: single
sitemap: true
permalink: /research/
author_profile: true
toc: true
toc_label: "Research"
toc_icon: "gear"
toc_sticky: true
---

Some of the research I've done in my undergrad:
- Investigation for clamp numbers on bent pipe for FIV reduction
- Optimization of Supercritical CO2 Brayton cycle with ejector and VCAR refrigeration
- Non-linear vibration testing for sandwich composite structure




## Investigation for clamp numbers on bent pipe for FIV reduction

<figure>
  <img src="/assets/images/Pipe pic.png" width="1000px" alt="">
  <figcaption>Pipe and clamp structure geometry for 90 degree bent section for high speed superheated steam flow.
</figcaption>
</figure>

Turbulent flows can often affect the structural integrities of pipe while experiencing flow discontinuities such as bends and tees, leading to Flow-Induced Vibration (FIV). Our study explores this phenomena for an industrial pipe section transporting high speed (50-62 m/s), high pressure (12.58 MPa) superheated steam (350C) based on one-way Fluid-Structure Interaction (FSI) methodology. Additionally, a preliminary study for vibration reduction was done by incorporating 13 possible clamp placements and simulating by placing one clamp for each simulation. We used RANS based turbulent model to simulate pressure and velocity distribution for the mass flow rates of 180, 200 and 220kg/s. The total pressure was the imported to transient structural to obtain a consistent vibration signal in the form of acceleration, investigate the possible locations for placing the clamp, and investigate how much the vibration frequency fluctuates after clamping. Our result showcased an average reduction of total acceleration and displacement by 31% for placing a single clamp at the inlet section. This number goes upto 35% if another clamp is added at the outlet section. 

**Contribution:** I proposed the methodology for adding clamps at equal spacing for reduced total acceleration and displacement and using three different mass flow rates for increased effieciency. I analysed the total acceleration and deformation of the transient structural by extracting these time-domain data from ANSYS. I imported these to a Python code I wrote by myself to convert time domain data to frequency domain using Fast Fourier Transform Algorithm (FFT). 

## Optimization of Supercritical CO2 Brayton cycle with ejector and VCAR refrigeration

<figure>
  <img src="/assets/images/SCO2 cycle.jpg" alt="">
  <figcaption>Schematic of cascaded Supercritical CO2 recompression Brayton cycle with transcritical CO2 ejector refrigeration cycle and flash tank enhance vapor absorption refrigeration cycle.  
</figcaption>
</figure>

Recompression Brayton Cycle using Supercritical CO2 although highly efficient for clean power generation, the heat wasted is not insignificant and leaves room for improvement to achieve higher thermal efficiency. To address this issue, the heat rejected was utilized for additional cooling load by introducing a Flash tank enhanced compression absorption refrigeration system with the Ejector-enhnaced transcritical CO2 refrigeration system. Parametric analyses was done in Python on seven different parameters and Multi-Objective Optimization was used to identify ideal parameters. For the Multi-Criteria Decision Making, NSGA-II and TOPSIS methods were used which yielded 16.14% and 4.4% improved thermal and exergy efficiency respectively.

**Contribution:** I reviewed the literatures on the Ejector-assisted transcritical CO2 refrigeration cycle and proposed a solution on how to integrate the cooling load. I performed the model validation of the old and proposed model using CoolProp Library and for the parametric analysis, I did the exergy analysis to measure the efficiency increase. Additionally, all the visuals for cycle schematics and P-h diagrams are made by me. 

## Non-linear vibration testing for sandwich composite structure

<figure>
  <img src="/assets/images/sandwich.jpg" alt="">
  <figcaption> Simulink model of 3DOF spring mass damper system to simulate non-linear behaviour of the composite.
</figcaption>
</figure>

A simulink model comprised of 3DOF spring mass damper system was used to check the nature of the vibration result. An experimental setup was built to test the presence of nonlinearity in different sandwich specimen. The specimen was fabricated using butyl rubber as core sandwiched between two stainless steel plates joined with adhesive. 

**Contribution:** I designed and fabricrated the specimen holder stand. I also fabricated two specimens of varying lenghts and designed a SIMULINK model in MATLAB to compare the non-linearity with the experimental findings.






