---
title: "uFluidic Device"
excerpt: "A micro-fluidic device that sorts pellets using pinch flow seperation"
header:
  image: /assets/img/SyringePumpTop.png
  teaser: /assets/img/SyringePumpCAD.png

# Introduction

Microfluidic devices are small-scale systems that manipulate fluids at the microliter or nanoliter scale, allowing precise control of fluid flow. 

Pinch Flow Fractionation (PFF) is a microfluidic sorting technique that separates particles based on their size. It works by introducing two streams into a channel of minimal area, where a pinching flow constrains the particles to a narrow region. As the flow expands at a downstream sorting region, larger particles experience greater lateral displacement than smaller ones, leading to size-based separation at different outlet channels.
   
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
