---
title: "Skate Mount"
layout: single
classes: wide
author_profile: false
sidebar:
nav: false

category: fabrication
excerpt: "Generative Design SLS Truck Hanger + Motor Mount"

header:
    image: /assets/img/AssemblySkate.png
    teaser: /assets/img/AssemblySkate.png

gallery:
    - url: /assets/img/SkateBoardMountrenderpic.png
      image_path: /assets/img/SkateBoardMountrenderpic.png
      alt: "Picture of Skate Mount"

---

<style>
.gallery img {
    max-width: 300px;
    height: auto;
    display: block;
    margin: 10px auto;
}
</style>

# Powder Bed Fusion + Generative Design
The combination of generative design and powder bed fusion represents a major shift in modern engineering design, particularly in aerospace and automotive industries. Generative design enables engineers to explore a wide range of optimized geometries based on loads, constraints, and materials, while powder bed fusion allows these complex geometries to be physically manufactured without the limitations of traditional processes. This pairing is especially powerful because it not only reduces weight but also enables part consolidation, replacing multi-component assemblies with a single optimized structure. In aerospace applications, where weight reduction directly improves performance and efficiency, this integration has become increasingly valuable.

# Generative Design in the Aerospace field
A relevant commercial example is the redesign of an aeronautical tail landing gear component using generative design and additive manufacturing. In this case, a multi-part assembly connected through bolts was consolidated into a single component optimized for additive manufacturing. The design process included defining preserve geometry, applying realistic load cases such as landing and steering forces, and evaluating multiple generative outcomes before selecting the optimal solution. The final component achieved a mass reduction of approximately 50% while maintaining structural requirements. This example demonstrates how generative design, combined with powder bed fusion, can significantly reduce part count, improve performance, and simplify manufacturing.

# Loads in Generative Design
Generative Design depends heavily on the accurate definition of load cases. In this skateboard truck hanger project, load cases were selected based on the physical interactions between the rider, the ground, and the motor system. A vertical load was applied at the axle to represent the rider’s weight, accounting for both static and dynamic effects during riding. Lateral loads were included to simulate turning and carving, where leaning generates sideways forces. A tangential force was applied at the motor mount to represent belt-driven torque from the brushless DC motor, carefully aligned with the belt direction to reflect real torque transmission. Additionally, a longitudinal force was applied to represent braking, and an impact load was applied at one axle end to simulate uneven terrain or sudden contact with obstacles.
These forces were determined using simplified physical reasoning, breaking down real-world conditions into dominant force components. While this approach captures the main structural behavior, it also highlights a limitation of generative design: the results are only as accurate as the assumptions made. Improvements to this process could include dynamic simulations, experimental measurements, or more advanced modeling of contact and time-dependent forces. However, for a generative design workflow, these simplified load cases provide a practical balance between realism and computational efficiency.

# Contrast between AlSi10Mg and 17-4 PH stainless steel:
The comparison between the AlSi10Mg and 17-4 PH stainless steel outcomes illustrates how material properties significantly influence optimized geometry. AlSi10Mg, a lightweight aluminum alloy commonly used in additive manufacturing, resulted in a design with thicker members and more distributed material to maintain strength and stiffness. In contrast, the 17-4 PH stainless steel design featured thinner, more refined structures due to its higher strength and stiffness. However, despite this structural efficiency, the stainless steel design had a higher overall mass because of its greater density. This demonstrates an important trade-off in generative design: stronger materials allow for more compact geometries, but do not necessarily produce lighter components. For this skateboard application, where weight plays a critical role in performance and maneuverability, the aluminum design provides a better balance between strength and mass.

# Drawbacks
While generative design is a powerful tool, it is not without limitations. One major drawback is its dependence on accurate input conditions. If loads or constraints are poorly defined, the resulting design may be unrealistic or unsafe. Additionally, generative design often produces highly organic geometries that can be difficult to interpret, modify, or integrate with existing components. These designs frequently require post-processing to ensure proper clearances, manufacturability, and assembly functionality. Computational cost is another challenge, as running multiple design iterations can be time-consuming. Furthermore, most generative design tools rely on simplified static analysis and may not account for fatigue, wear, or long-term performance.

# Application of Generative Design
Despite these drawbacks, generative design is highly useful in applications where performance optimization and weight reduction are critical. Aerospace, automotive, and robotics industries benefit the most, particularly in low-volume, high-performance components where additive manufacturing is feasible. In these contexts, generative design enables engineers to discover efficient load paths and create structures that would be nearly impossible to design manually.

# Conclusion
The integration of generative design with powder bed fusion enables engineers to move beyond traditional design limitations, achieving lightweight, consolidated, and high-performance components. However, its effectiveness depends on careful setup, accurate load definition, and thoughtful interpretation of results. As demonstrated in both the aerospace example and the skateboard truck design, generative design is a powerful tool but one that still relies heavily on engineering judgment to produce practical and reliable solutions.


# Forces

| Name of Forces                    |   Magnitude    |     Location    |           Short Rational                        |  
|-----------------------------------|----------------|-----------------|-------------------------------------------------|
| Vertical Force                    |      1000 N    |      AXLE       |    Represents rider load with safety margin     |    
| Lateral Force                     |       400 N    |     AXLE        |        Simulates turning/carving                |   
| Motor Force                       |       400 N    |   Motor mount   |    Derived from 8 Nm torque                     |  
| Braking Force                     |       300 N    |       Axle      |   Simulates deceleration                        |  
| Impact Load                       |       35 N     |  One Axle  end  |      Simulates bump/landing                     |  


{% include gallery caption="Gallery" %}

# Assembly of fInal Nylon Model
<iframe src="https://a360.co/48mwE8c" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>

# Generative Design with 17-4 PH
<iframe src="https://a360.co/4vXb3wZ" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>

# Generative Design with ALSi10Mg
<iframe src="https://a360.co/4w2SDeA" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>

# Edited final Design with Nylon 12
<iframe src="https://a360.co/48uEZ9N" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"> </iframe>
