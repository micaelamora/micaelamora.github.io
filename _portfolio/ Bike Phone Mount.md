---
title: "Bike Mount"
layout: single
classes: wide
author_profile: false
sidebar:
  nav: false

category: fabrication
excerpt: "Bike mount for phones"

header:
  image: /assets/img/bikemount.png
  teaser: /assets/img/bikemount.png

gallery:

  - url: /assets/img/bikemount.png
    image_path: /assets/img/bikemount.png
    alt: "Picture of bike mount"
  - url: /assets/img/ball of ball bearing .png
    image_path: /assets/img/ball of ball bearing .png
    alt: "Ball bearing"
  - url: /assets/img/squareball.png
    image_path: /assets/img/squareball.png
    alt: "Square of Balle Bearing"
  - url: /assets/img/rendering view.png
    image_path: /assets/img/rendering view.png
    alt: "Rendering view"

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
This project was completed using a top-down modeling approach, where all components of the bike phone holder were designed within a single assembly file and referenced from shared geometry. The handlebars and phone were first created/imported as base components and used as the primary references to drive the design.

From there, each component of the holder (clamp, rotating interface, and phone grip) was modeled in context, ensuring that all parts aligned correctly and maintained proper clearances. As-built joints were then used to define relationships between components.

# This approach allowed for:

* Consistent alignment between parts
* Efficient iteration by modifying key parameters
* Reduced assembly errors since all parts were designed relative to each other

Additionally, parametric dimensions (such as phone width range and rotation clearances) were used so adjustments could be made quickly to accommodate tolerances or design changes.

# Rationale behind the design
The design was developed by prioritizing secure gripping, tool-free operation, and rotational functionality.

* Key parts of the design included:

  * A handlebar clamp sized to fit the provided 22.2 mm grip diameter
  * A rotational interface to allow switching between portrait and landscape
  * A flexible phone gripping mechanism to accommodate different phone sizes

The design prioritizes:

Stability under vibration
Ease of use without tools during normal operation
Compatibility with a range of phone sizes

• How did you implement the detent mechanism? Does it work well? 

• Did you have to change any dimensions to account for the 3D printing process? 

• What type of 3D printing did you use? Why? 

▪ Brief Assembly/use instructions 
▪ Which printing technology and why did you use for each part?  
o Embedded Interactive CAD model 

▪ Real-life .GIF of the holder rotating between landscape and portrait  
▪ Fusion Rendering of phone holder with phone on it.  
▪ Cross-section view of internal rotation mechanism.  This can be a 
screenshot of the design workspace with the section analysis tool.  
▪ Individual images of each of the top-down components. This can be real
life or Fusion renderings. 

  
{% include gallery caption="Gallery" %}

# CAD Model 
<iframe src="https://a360.co/482nFJ5" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>
