---
title: "uFluidic Device"
excerpt: "A micro-fluidic device that sorts pellets using pinch flow seperation"
header:
  image: /assets/img/FluidicCAD.png
  teaser: /assets/img/FluidicCAD.png
  
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
# Discussion

Resin-printed molds are coated with parylene to prevent adhesion of PDMS, enabling easy demolding and preserving the mold for repeated use. Additionally, the smooth coating enhances microchannel accuracy and reduces defects that could impact fluid flow. The physical channels of the device plays a significant role in sorting efficiency. The pinch width is 0.6 mm, which is slightly larger than the large particles, being 0.5 mm in diameter. The smaller particles were much smaller. This allows the center of mass of the different sizes to effectivly be pushed up against the side of the model and thus in a different flow stream. This precisely controls the initial particle alignment, and when the channel width suddenly increases to 16 mm, the particles become sorted by an amount proportional to their relative position from the wall in the pinched segment. To maintain uniform flow distribution among the outlets, the channel geometry was designed with symmetrical features that maintained similar cross sectional areas so that flow resistance was carefully balanced through the pathways.

The test results provided no accurate assessment of the viability of the design. The set up and flow rate caused eddies that formed in multiple designs being tested. This broke the expectation of laminar flow in the microfluidic device, thus not providing any substantial evidence of a favorable design or unfavorable design.

---

---
# Pictures
<img src="/assets/img/IMG_0497.png" >


# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
