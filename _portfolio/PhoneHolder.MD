---
title: "Phone Holder"
excerpt: "Phone Holder made to rotate between four different positions and clamp onto bike handle bars."
header:
  image: /assets/img/PhoneHolderCAD.png
  teaser: /assets/img/PhoneHolderCAD.png

---

# Background on Top Down Modeling

---
Top-down modeling is a CAD design strategy where a single master part or assembly drives the entire design process. Rather than design each part individually in their isolated workspace like in Bottom-Up Modeling, Top Down Modeling introduces each part to the others on creation, allowing for mates and constraints to be integrated with ease. Since dimensions are shared by multiple components, this method of modeling allows for updated dimensions to iterate throughout the entire design, leading to an easier implementation of changes.

---
# Design Process

The design process began with the bottom clamp that attaches to the Bike Handle. This was selected due to it being the part that is fixed in the model. While other pieces rotate, the bottom clamp will be fixed. To achieve the appropriate friction fit between the clamp and bike, the clamp does not form a complete circle, thus allowing screws to compress the top and bottom to the handlebar.

The next piece to be modeled was the rotating capsule. This was split into two different components for timeline simplicity. The locking mechanism was implemented in this step. Space had to be made for a spring and ball bearing, which would compress into divets made in the rotating piece. To do this, an extrusion was made off to one side of the circular base. This hollow segment would house the spring such that it was only slightly compressed.

The rotating piece was designed as a simple circle with four shallow divots. This allows for it to rotate between these four positions. However, to attach to the phone holder, this piece needed a smaller extrusion on top with four heat inserts. This also allowed for a lid for the rotating capsule to be constructed so as to attach the rotating piece and phone holder to the capsule and handlebar clamp.

The phone holder was designed to be flexible, allowing for a phone to be easily slid into, and out of the holder.

The design material differed from part to part. TPU was the choice for the phone holder itself, This allows it to bend to allow the phone to be easily removed and put on, while still having enough rigidity to keep the phone stable. Furthermore, in case of blunt impacts, TPU provides excellent protection by absorbing most of the shock. The rest of the parts were printed with PLA. These parts needed to be rigid to provid the necessary structural integrity needed to maintain the structure and locking mechanism. The clamp, while in this case printed in PLA, can be printed with either, as some elastic deformation is needed to provide enough friction on the handlebars.

---
# Assembly Instructions

On the eight holes on the Handlebar Clamp, M3 heat inserts must be set. Four M3 heat inserts must also be set in the Rotating Base component in each of the outer holes. On the Rotating Piece, four M3 heat inserts must be placed as well. Once this is done, use M3 screws to join the Rotating Base with the Handlebar clamp, then a spring and ball bearing of size no larger than 6 mm must be inlayed in the Rotating Base along with the Rotating Piece before the Rotating Lid is layed on top and screwed down using the heat inserts. The Phone Holder must then be aligned and screwed down to the rotating peice, joining the entire assembly together.


---
# Phone Holder

<img src="/assets/img/PhoneHolderSide.png" >
<img src="/assets/img/PhoneHolderTop.png" >

---

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



