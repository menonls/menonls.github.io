---
title: "Multi-Material Pliers"
excerpt: "Multi Material Pliers made from PLA and TPU-90, easy assembly"
header:
  image: /assets/img/MultimaterialPliers.png
  teaser: /assets/img/MultimaterialPliers.png

---

# Background on Multimaterial Printing

---
Multimaterial printing is an advanced 3D printing technique that uses multiple materials in a singular print, unlike traditional 3D printing which maintains a constant singular material throughout. One of the primary advantages of this technology, is its ability to integrate these seperate materials seamlessly without the need for additional screws, heat inserts, or bolts. Multimaterial printing joins these parts together as they are being constructed layer by layer, enhancing functionality and saving space within the design itself.

This technology has greatly expanded the capabilities of print in place design - where the product is fully constructed and assembled on the print bed itself. Traditional mechanical components often required some assembly of ridged and elastic parts before being complete; however, with Print in place, these elements can be integrated on the print bed itself, allowing for structures that could normally be impossible to produce, such as interlocking circles. Common materials used in print in place applications are ridged materials like PLA and PETG, along with flexible materials like TPU. Applications of this prosthetic components that require both a ridged and flexible segment, pliers and wrenches that are integrated with hinges for immediate use, and toys/games that require interlocked components.

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


