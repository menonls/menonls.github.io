---
title: "Generative Design - Robotic Palm"
excerpt: "A palm designed for a robotic hand, houses 8 servos and allows for further thumb design."
header:
  image: /assets/img/GenerativePalmCAD.png
  teaser: /assets/img/GenerativePalmCAD.png

---

# Project Description

---
This project features a PLA 3D-printed robotic hand designed for two degrees of freedom on each finger (2-DoF), enabling both flexion/extension at the knuckle and interphalangeal joints. The model uses a tendon driven motion control, where tendons (Fishing line) attach both the distal and proximal phalanx to embedded servos to replicate finger movement.
The model can be remotely operated using a control glove, which tracks finger positions using a 3D-printed PLA linkage with two potentiometers per finger. This setup allows for separate, independent control of each finger on the sagittal plane.

---
# Design Process

Features and Simplifications
•	Flexion/Extension at the PIP and DIP joint were connected by a crossed belt drive. 
o	Reasoning: In the human hand, these joints naturally move synchronously during grasping, so coupling them mechanically still allows for realistic, functional motion.
o	Implementation: A crossed belt drive ensures proportional movement between the two joints with only one input. This method also allows for the use of bearings, creating a smooth interface between different joints.
•	Abduction/Adduction at the MCP Joint was removed entirely.
o	Reasoning: During grasping motion, this movement is minimized as the human hand scrunches together forcing all the fingers to be parallel with one another.
•	Elastic elements would be used to extend all joints once flexion is relaxed.
o	Reasoning: This approach eliminates the need for actuators to return their finger to their default state, thus cutting cost and weight.
o	Implementation: Elastic bands were fastened around M2 Screws set in heat inserts on the back of the finger. This method was the least invasive and easiest to tension properly and repair. Tension and torsional springs were considered, however, ultimately discarded due to unknown spring constants and forces needed.

---
# Dimensioned part

<img src="/assets/img/RoboticFingerDrawing.png" >
<img src="/assets/img/RoboticPalmDrawing.png" >
The inner square is 50 mm x 50 mm, with the surrounding trapezoids being 5 mm on the short side, 10 mm on the long side, and 5 mm wide. The TPU was printed with a grid infill, no top and bottom layers, and 4 outside layers. The PLA was printed with 7 outside layers, no infill, and not top and bottom layers.

---
# Assembled Pliers

<img src="/assets/img/MultiMaterialGIF.gif" >

---

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
