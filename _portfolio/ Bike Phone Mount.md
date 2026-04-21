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
  - url: /assets/img/phoneholder.mp4
    image_path: /assets/img/phoneholder.mp4
    alt: "Pliers closing and opening"

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

  * A handlebar clamp sized to fit the provided 25.4 mm grip diameter
  * A rotational interface to allow switching between portrait and landscape
  * A adaptable phone gripping mechanism to accommodate different phone sizes

The design prioritizes:

  * Stability under vibration
  * Ease of use without tools during normal operation
  * Compatibility with a range of phone sizes

# Detent Mechanism 
The detent mechanism was implemented using a spring-loaded ball bearing system, consisting of a compression spring and a steel ball bearing housed within a 3D printed cavity.

* The design works as follows:

  * A compression spring is placed inside a cylindrical pocket within the stationary component
  * A ball bearing sits on top of the spring, partially protruding from the housing
  * The rotating component contains predefined recesses (detent pockets) at 0° and 90°, corresponding to portrait and landscape orientations
  * As the mount rotates, the ball is pushed upward by the spring and snaps into these recesses, creating a noticeable “click”


* Performance:
The detent mechanism functions effectively, providing a distinct and repeatable engagement at both orientations. The spring force and recess depth were critical parameters; if too weak, the phone could rotate unintentionally, and if too strong, rotation becomes difficult. The final design achieves a balance between ease of rotation and secure positioning under typical riding vibrations.

# 3D printing Method
All components were fabricated using FFF with PLA filament.
* Several design modifications and an assembly were made to account for perfect fitting of the parts:

  * Clearances of approximately 0.2–0.5 mm were added between mating parts
  * Holes for screws were picked to be the diameter of the screw

* Each part was oriented and designed differently based on its function:
  * Clamp: Printed to maximize strength along the layer direction to resist tightening forces
  * Rotating interface: Printed to preserve circular accuracy and smooth motion
  * Phone holder arms: Printed to balance strength and flexibility for gripping the phone
  * Small parts were placed in the most optimal position to reduce support material

PLA was selected because:

It is easy to print with minimal warping
It provides good dimensional accuracy for mating parts
It is sufficient for prototyping and functional testing

{% include gallery caption="Gallery" %}

# CAD Model 
<iframe src="https://a360.co/482nFJ5" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>
