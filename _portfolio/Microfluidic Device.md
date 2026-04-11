---
title: "Microfluidic Device"
layout: single
classes: wide
author_profile: false
sidebar:
  nav: false

category: fabrication
excerpt: "3D printed mold for Microfluidic device"

header:
  image: /assets/img/mainpictureofmicrofluidci.png
  teaser: /assets/img/mainpictureofmicrofluidci.png

gallery:
  - url: /assets/img/plasma1.jpg
    image_path: /assets/img/plasma1.jpg
    alt: "Plasma Treating"
  - url: /assets/img/dimensionsof1.png
    image_path: /assets/img/dimensionsof1.png
    alt: "dimensions of the mold"
  - url: /assets/img/Printed Parts 2.jpeg
    image_path: /assets/img/Printed Parts 2.jpeg
    alt: "Printed Mold"
  
    
---

<style>
.gallery img {
    max-width: 300px;
    height: auto;
    display: block;
    margin: 10px auto;
}

.video-box {
    max-width: 300px;
    margin: 20px auto;
    text-align: center;
}

.video-box video {
    width: 100%;
    border-radius: 10px;
    display: block;
}
</style>

<h2>Introduction:</h2>

Pinched Flow Fractionation (PFF) is a microfluidic technique used to separate particles based on size. In a microchannel with a narrow (pinched) segment, particles are aligned against one sidewall by a particle-free fluid stream. As the channel widens, the flow profile spreads the particles laterally, separating them according to their size.

PFF is a versatile and promising technology with applications in biomedical, environmental, and industrial fields. It is widely used to isolate and analyze cells, viruses, extracellular vesicles, blood components, metal particles, polymers, and more. In biomedicine, PFF supports disease detection, biomarker discovery, and drug delivery optimization by enabling precise size-based particle separation. This capability helps advance personalized medicine and targeted treatments.

Advantages of PFF include:
* High separation efficiency
* Continuous processing
* Low-cost, simple fabrication
* Reduced risk of clogging compared to traditional filters

These features make PFF a cost-effective and reliable solution for particle sorting across a wide range of applications.

<h2>Design:</h2>

The design selected for this device was a symmetric configuration consisting of three outlets and two inlets. The overall concept was inspired by the work of Nan Xiang and Jie Wang on coupling inertial microfluidics with deterministic lateral displacement (DLD), which enables precise, continuous, and size-based particle separation without the need for external forces or labeling. In their approach, particles are first focused using inertial effects and then further separated using a structured array that laterally displaces particles based on size differences. While their design incorporates a spiral channel as an initial focusing stage followed by a DLD array, the device developed here simplifies and adapts these principles to better align with the constraints of the assignment. Specifically, the inlet region does not include a spiral geometry and instead uses two straight inlets to control flow conditions before entering the main sorting region. Additionally, the design focuses on maintaining symmetric flow distribution across three outlets while still leveraging the core idea of size-based separation through controlled streamline behavior. These modifications preserve the fundamental separation mechanism described in the literature while making the device more feasible to fabricate and test within the scope of this project.

$$
Y_0 = \left(w_p - \frac{D}{2}\right)\frac{w_b}{w_p}
$$


<h2>Instructions:</h2>

Creating a microfluidic device using resin printing begins with designing a mold in CAD software such as Fusion 360, where channel dimensions, inlets, and outlets are carefully defined based on printer resolution and desired flow behavior. This mold is then fabricated using an SLA resin printer, ensuring that the bottom surface is perfectly flat to enable proper sealing later. After printing, the mold undergoes post-processing, including washing in isopropyl alcohol to remove uncured resin, drying thoroughly, and a brief UV cure to solidify the surface while maintaining smooth channel features. Once cleaned and prepared, polydimethylsiloxane (PDMS) is mixed, poured over the mold, and degassed to eliminate bubbles before being cured at an elevated temperature. After curing, the PDMS is peeled off the mold, revealing the embedded microfluidic channels. The PDMS device is then bonded to a glass slide, typically using plasma treatment, to seal the channels and create a functional device. Finally, tubing is connected to the inlets and outlets, and the device is tested using controlled flow from syringe pumps to evaluate performance and ensure proper fluid behavior. 

<h2>Discussion:</h2>

Resin printing was chosen because it provides high-resolution features and smooth surfaces, which are essential for fabricating small and precise microfluidic channels. Compared to other methods like FDM printing, it allows for better detail and more reliable device performance. To scale the design or handle a wider range of particle sizes, channel dimensions and sorting geometries can be adjusted, or multiple stages can be added to separate different size ranges more effectively. The lower limit of particle size that can be separated is mainly determined by the printer resolution and channel surface roughness, since very small particles are more affected by imperfections and flow disturbances. A key challenge in this design was that the triangular sorting features tended to trap air bubbles, which disrupted flow and reduced separation efficiency.



<h2>Multimedia:</h2>



{% include gallery caption="Gallery" %}

<div class="video-box">
  <video controls playsinline preload="metadata">
    <source src="/assets/img/Microfluidics.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><strong>Working Microfluidic</strong></p>
</div>

<h2>CAD Model</h2>

<iframe src="https://a360.co/4slzeCU" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

<h2>References:</h2>
* [A comprehensive review of pinch flow fractionation in microfluidics: From principles to practical applications - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0255270124004252#sec0014)
* [Microfluidics for separation, detection, and engineering of extracellular vesicles - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0169409X2600044X#f0030)
* [Precise Size-Based Cell Separation via the Coupling of Inertial Microfluidics and Deterministic Lateral Displacement - Analytical Chemistry](https://pubs.acs.org/doi/10.1021/acs.analchem.9b02863?src=getftr&utm_source=sciencedirect_contenthosting&getft_integrator=sciencedirect_contenthosting) 
* [Particle separation and sorting in microfluidic devices: a review](https://www.academia.edu/38077515/Particle_separation_and_sorting_in_microfluidic_devices_a_review)
* [Design advances in pinched flow fractionation for enhanced particle separation in microfluidics - Lab on a Chip (RSC Publishing)](https://pubs.rsc.org/en/Content/ArticleLanding/2025/LC/D5LC00497G)
* [Separation enhancement in pinched flow fractionation](https://pubs.aip.org/aip/apl/article/93/20/203507/336137/Separation-enhancement-in-pinched-flow)
