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

Palm Design
A palm was designed on Fusion360 using the generative design tool (as seen in Figure 3) to approximate the best stiffness to mass design, while still allowing for the part to be Filament or SLS printed. All motors needed to control the model are housed within, eliminating the need for separate housing. Though the thumb was not designed and presented due to Arduino input/output pin constraints, this version of the palm was made to allow for a saddle joint to easily be built in place to allow for both adduction/abduction and flexion/extension of the thumb.

---
# Dimensioned part

<img src="/assets/img/RoboticFingerDrawing.png" >
<img src="/assets/img/RoboticPalmDrawing.png" >


---
# Assembled Pliers

<img src="/assets/img/MultiMaterialGIF.gif" >

---

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
