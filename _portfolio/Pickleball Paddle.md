---
title: "Pickleball Paddle"
layout: single
classes: wide
author_profile: false
sidebar:
  nav: false

category: fabrication
excerpt: "3D Printed Pickleball Paddle"

header:
  image: /assets/img/Paddleboardhorizontal.png
  teaser: /assets/img/Paddleboardhorizontal.png

gallery:

  - url: /assets/img/bikemount.png
    image_path: /assets/img/bikemount.png
    alt: "Pickleball Paddle"
  - url: /assets/img/topview.jpeg
    image_path: /assets/img/topview.jpeg
    alt: "Pickleball Paddle"

---

<style>
.gallery img {
    max-width: 300px;
    height: auto;
    display: block;
    margin: 10px auto;
}
</style>

# Description of the Prototype
This project focuses on the design, prototyping, and optimization of a fully 3D printed pickleball paddle that complies with official USA Pickleball standards. The paddle was designed for functionality, durability, and performance, while leveraging modular design principles.

# Paddle Design & Rule Compliance:

The paddle was designed to meet the 2026 USA Pickleball Official Rulebook specifications, including size constraints (maximum combined length + width of 24 inches and length ≤ 17 inches) and surface requirements. The face geometry was modeled to maintain a smooth, rigid, and non-compressible surface, avoiding textures that could introduce excessive spin or violate roughness limits.

Due to printer size constraints of the build plate, the paddle was split into two primary components: the paddle face and the handle. These were assembled using M4 heat-set inserts and bolts, ensuring strong mechanical fastening while allowing disassembly if needed. The final structure was tested for durability under gameplay conditions, ensuring it could withstand repeated impacts while maintaining structural integrity.


# Weight & Mass Balance Optimization 
The paddle was optimized for a midweight configuration (17 oz), providing a balance between control and power . Weight reduction strategies included internal infill optimization and selective material distribution, while maintaining sufficient stiffness in the paddle face.

Mass balance was a key design consideration, as it directly influences swing speed and control. The center of mass was adjusted by redistributing material between the head and handle, allowing for a slightly head-light configuration to improve maneuverability and reaction time. Iterative prototyping and testing were used to refine this balance, ensuring the paddle felt responsive without sacrificing hitting power. This process highlights the importance of integrating mechanical design with user-specific performance goals in sports equipment engineering.

# 3D printing Method
All components were fabricated using FFF with ABS filament.
* Several design modifications and an assembly were made to account for perfect fitting of the parts:

  * Clearances of approximately 0.2–0.5 mm were added between mating parts
  * Holes for screws were picked to be the diameter of the screw

* Each part was oriented and designed differently based on its function:
  * Clamp: Printed to maximize strength along the layer direction to resist tightening forces
  * Rotating interface: Printed to preserve circular accuracy and smooth motion
  * Phone holder arms: Printed to balance strength and flexibility for gripping the phone
  * Small parts were placed in the most optimal position to reduce support material

ABS was selected because:

It is easy to print with minimal warping
It provides good dimensional accuracy for mating parts
It is sufficient for prototyping and functional testing

{% include gallery caption="Gallery" %}

# CAD Model 
<iframe src="https://a360.co/4cAopru" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>
