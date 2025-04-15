---
title: "Multi-Material Pliers"
excerpt: "Multi Material Pliers made from PLA and TPU-90, easy assembly"
header:
  image: /assets/img/MultimaterialPliers.png
  teaser: /assets/img/MultimaterialPliers.png

---

# Background on Top Down Modeling

---
Top-down modeling is a CAD design strategy where a single master part or assembly drives the entire design process. Rather than design each part individually in their isolated workspace like in Bottom-Up Modeling, Top Down Modeling introduces each part to the others on creation, allowing for mates and constraints to be integrated with ease. Since dimensions are shared by multiple components, this method of modeling allows for updated dimensions to iterate throughout the entire design, leading to an easier implementation of changes.

---
# Design Process

The multimaterial pliers used TPU-90 as the central component with PLA for the snout and handles. By squeezing the handles, the central TPU square is elongated, causing the snout on the opposite side to pinch together. The hollowness of the snout allows for some bending to exist in the part, allowing the pliers to deform slightly to achieve a better grip along a greater area than what would be found in a filled in segment.

To a achieve a well-fitting TPU-PLA interface, the tolerances between the sperate components had to be tested. The first iteration had a gap of 0.5 mm in between the TPU-PLA ridges. While this slid in quite easily, it did not provide enough friction to keep the handles from slipping out of the TPU square. The second iteration was printed with no tolerance between parts. This was much better than the first iteration. Due to TPU's natural elasticity, The material deformed to fit and provided much more friction than the original.

To save material and time, only the outside border of the PLA handle and snout was printed. This in turn allowed the PLA to to bend as more force was applied on the handle, allowing the a greater area along the snout to touch together, rather than just the tip.

The TPU square went through a couple iterations. Originally, the center was cordoned off into squares in line with the outer square; however, this caused the deformation to not be in line with its diagonal, which is what was required to allow for the clamping mechanism to properly function. This was fixed by rotating the inner mesh by 45 degrees, allowing for a diagonal deformation.

---
# Dimensioned part

<img src="/assets/img/MultimaterialDrawing.png" >

The inner square is 50 mm x 50 mm, with the surrounding trapezoids being 5 mm on the short side, 10 mm on the long side, and 5 mm wide. The TPU was printed with a grid infill, no top and bottom layers, and 4 outside layers. The PLA was printed with 7 outside layers, no infill, and not top and bottom layers.

---
# Assembled Pliers

<img src="/assets/img/MultiMaterialGIF.gif" >

---

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



