---
title: "Multimaterial Pliers"
layout: single
classes: wide
author_profile: false
sidebar:
  nav: false

category: fabrication
excerpt: "Pliers made out of TPU and PLA"

header:
  image: /assets/img/render 2 white bacground.png
  teaser: /assets/img/render 2 white bacground.png

gallery:
  - url: /assets/img/for_gallery_1.jpeg
    image_path: /assets/img/for_gallery_1.jpeg
    alt: "Pliers 1"
  - url: /assets/img/for_gallery_2.jpeg
    image_path: /assets/img/for_gallery_2.jpeg
    alt: "pliers 2"
  - url: /assets/img/for_gallery_3.jpeg
    image_path: /assets/img/for_gallery_3.jpeg
    alt: "Pliers 3"
  - url: /assets/img/WhatsApp Video 2026-02-08 at 12.00.31.mp4
    image_path: /assets/img/WhatsApp Video 2026-02-08 at 12.00.31.gif
    alt: "Pliers picking up resistors"
  - url: /assets/img/WhatsApp Video 2026-02-08 at 12.00.59.mp4
    image_path: /assets/img/WhatsApp Video 2026-02-08 at 12.00.59.gif
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


# Description of the prototype 
These 15 cm needle-nose pliers are a hybrid print + assembly design: two rigid PLA halves (white) form the handles and jaws, and a single red TPU spring element gives the pliers a reliable return/opening action. The assembly is a 3-part press-fit (2 rigid pieces + 1 elastic spring) printed in a Vorno 3D printer. The approach keeps the crisp, rigid gripping surfaces where you need them and uses a compliant elastomer only for the spring function.

# Design Features 
* **Materials:**
  * Handle & tips: White PLA (rigid, good surface finish for gripping)
  * Spring center: Red TPU (95A recommended for balance of flexibility + durability)
* **Geometry:**
  * Long, narrow jaws with slightly textred tip faces for  grip on small resistors
  * Spring center geometry is a thin, square-shaped elastomeric element that sits inside mating cavities in the handle halves and is retained by tabs.
* **Assembly:**
  * Hand-press assembly only. Designed clearance lets the spring center be pushed into grooves and locked by small retention tabs. Step by step description below.
  

# Specifications 
* Overall length: 150 mm
* Tip Length: 55 mm
* Maximum jaw opening: 10 mm
* Parts: 4 x PLA rigid bodies +  1 x TPU spring
* Printer used: Voron 3D printerr
* Required post-processing: None (press-fit assembly only)
 

# Printing Setting 
 **Rigid PLA handles**
* Material: White PLA
* Fill density: 15%
* Supports: Everywhere
* Infill Pattern: Rectilinear
* Minimum shell thickness: 0.8 mm
* Top Infill Pattern: Monotonic

 **Spring Center**
* Material: Red TPU 95
* Fill Density: 31%
* Supports: Everywhere
* Infill Pattern: Grid
* Minimum Shell thickness: 0 mm
* Top Infill Patter: Monotonic


| Part                                           | Material     |
|------------------------------------------------|--------------|
| Center                                         | TPU          |
| Left Handle                                    | PLA          |
| Right Handle Body                              | PLA          |
| Left Tip                                       | PLA          |
| Right Tip                                      | PLA          |

  
{% include gallery caption="Gallery" %}

# CAD Model 
<iframe src="https://a360.co/4kj4Xla" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>


<h2> Assembly Steps: </h2>
* 1) Print the two PLA halves and the TPU spring.
* 2) Orient the rigid halves so mating cavities are aligned.
* 3) Press the TPU spring into one handle cavity until retention ribs engage.
* 4) Press the second handle over the exposed portion of the spring and snap the two halves together. Assembly should be manual.
* 5) Test action: pliers should open automatically; squeeze to close and pick up a resistor by the jaw tips.

<h2>Print-in-place: what it means & applications:</h2>

Print-in-place refers to models that print with moving or interlocking parts already assembled — no hardware or (sometimes) even post-print assembly required. Designers create negative clearances and compliant features so the parts separate or flex after printing.

* **Hinges & enclosures:** parametric print-in-place hinges and small hinged boxes that print fully assembled. Great for clips, cases, and foldable parts.
* **Compliant springs & living hinges:** flexible geometry printed in TPU (or thin PLA) used as a return or damping element — many community spring designs and tutorials exist
* **Mechanical linkages & snap-fit assemblies:** toy mechanisms, articulated figurines (print-in-place joints), and snap connectors that remove assembly steps — collections and tutorials how large sets of mechanisms that hobbyists and engineers use.

**Combination of materials to use for print-in-place:**
* 1) PLA (rigid) + TPU (flexible): the most common hybrid for small tools and compliant springs. PLA gives good surface detail and stiff jaws; TPU gives rubbery flex for springs or living-element functions. This combo is widely used in community designs  and is the combination suggested for your course project (95A TPU recommended for balance of stiffness/durability). 

* 2) PETG + TPU — PETG is tougher and more heat resistant than PLA and often bonds better to TPU in practice; useful for parts that must tolerate higher temperatures or slightly rougher handling. Community guides often suggest PETG when strength + slight flexibility.

* 3) Nylon + TPU or flexible nylons — used in industrial or advanced hobby prints for high-wear or high-cycle components; more challenging to print but durable. (Research literature also explores engineered blends/pellet co-extrusion for new multifunctional parts.)

* 4) Single-material print-in-place (thin PLA flexures) — for simple living hinges or snap joints designers sometimes make the entire mechanism from one rigid filament (thin section acts as a compliant hinge). This avoids adhesion issues but suffers fatigue and “crunchy” extrusion irregularities. Your project brief notes this tradeoff and permits the 3-part assembly to avoid single-material limitations.

<h2>Sources:</h2>
* thingiverse.com
* Maker World
* ScienceDirect



