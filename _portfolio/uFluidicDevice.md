---
title: "uFluidic Device"
excerpt: "A micro-fluidic device that sorts pellets using pinch flow seperation"
header:
  image: /assets/img/SyringePumpTop.png
  teaser: /assets/img/SyringePumpCAD.png
  
---

# Introduction

Microfluidic devices are small-scale systems that manipulate fluids at the microliter or nanoliter scale, allowing precise control of fluid flow. 

Pinch Flow Fractionation (PFF) is a microfluidic sorting technique that separates particles based on their size. It works by introducing two streams into a channel of minimal area, where a pinching flow constrains the particles to a narrow region. As the flow expands at a downstream sorting region, larger particles experience greater lateral displacement than smaller ones, leading to size-based separation at different outlet channels.

---
# Fabrication Process

CAD Model

A 3D model of the mold is designed using CAD software. The design includes features such as the pinch segment, sorting region, and outlet channels with specific dimensions to ensure proper fractionation. Two outlets were joined together to reduce the number of outlets needed, reducing the requirements of the set up.

Print and Cure Mold

The mold is fabricated using high-resolution resin 3D printing. This allowed the neccesary clearances needed to achieve the fine details for the microscopic particles that would be flowing through. The smoothness of each layer also allowed the mold to produce a result that was smooth enough to be bonded to a glass slide.

Parylene Coating

The printed mold is coated with a thin layer of parylene to enhance durability and prevent adhesion of PDMS during casting. Parylene also provides a smoother surface, reducing imperfections in the final device.

Cast PDMS

Polydimethylsiloxane (PDMS) is poured over the mold and cured at an elevated temperature. Once cured, the PDMS is carefully peeled from the mold, forming the microfluidic channel network.

Plasma Bond Glass Slide

The PDMS device is  bonded to a glass slide to create enclosed microfluidic channels. This bonding ensures a leak-proof system suitable for fluidic experiments.

---
# Features

The syringe pump delivers precise and smooth flow rates, essential for medical and laboratory applications. Key features include:
* Compatibility with 10 mL and 20 mL syringes without special tools.
* Motor-driven lead screw mechanism for fluid dispensing.
* Safety mechanisms like an end-of-stroke switch to prevent over-extension.
* Protected electronic components for durability and safety.

---
# Operating Instructions

* Fit filled syringes into the appropriate slots.
* Connect the Arduino board to a laptop and upload the AccelStepper code.
* Disconnect the Arduino from the laptop and connect it to the power supply.
* Plug the power supply into an outlet (yellow LED indicates idle state).
* Press the ON button to start the motor (green LED will light up).
* The motor will push the syringe plunger until it hits the OFF switch.
* Once the switch is triggered, the red LED lights up, and the motor stops.

---
# Used Parts
<img src="/assets/img/PartTable.png" >


# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
