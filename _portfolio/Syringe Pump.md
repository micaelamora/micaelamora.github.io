---
title: "Syringe Pump"
category: fabrication
excerpt: "Syringe Pump with interchangeable 5mL, 10mL, and 20mL syringes!"
header:
  image: /assets/img/linear rod actuator final assembly.png
  teaser: /assets/img/linear rod actuator final assembly.png
gallery:
  - url: /assets/img/syringe pump finished assembly.png
    image_path: assets/img/syringe pump finished assembly.png
    alt: "placeholder image 1"
  - url: /assets/img/side by side syringe hold.jpg
    image_path: assets/img/side by side syringe hold.jpg
    alt: "placeholder image 2"
  - url: /assets/img/remote controller box print pic.jpg
    image_path: assets/img/remote controller box print pic.jpg
    alt: "placeholder image 3"
---
# Description of the prototype


# Features of the design 


# Operating Instructions 

* **Step 1:** Place 10 mL or 20 mL in corresponding holes. The 10 mL holes are on the front side of the pump, and the 20 mL holes are towards the back side.
* **Step 2:** Press the black button, third from the left, to start the motion of the pump at 5 mL/min for a 20 mL syringe. To pause, press this button again. Motion will automatically stop when the syringe is empty.
* **Step 3:** To adjust the motion for a 10 mL syringe, press the red button directly to the right of the black button (the fourth button from the left).
* **Step 4:** Press and hold the first button to manually move forward. Press and hold the second button to manually move backward.
* **Step 5:** To set the speed using the knob, press the rightmost red button (5th from the left) and rotate the knob right to increase speed and left to decrease speed.
* **Step 6:** Due to prototyping limitations, the remote must be powered using a micro USB cable connected to a laptop or similar device. For future iterations, the remote will have a stand-alone power source. To turn on the syringe, flip the switch to the on position. To pause the syringe, flip it to the off position.

{% include gallery caption="Gallery." %}

  <!-- CAD Model Section -->
  <h2>CAD Model</h2>
  <iframe
    src="https://a360.co/4qGvStc?mode=embed"
    width="800"
    height="600"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0">
  </iframe>


 <h2>Table with off the shelf parts</h2>
 
| Supplies                                             | Quantity      |
|------------------------------------------------------|---------------|
| 250 mm lead screw with 2 mm pitch and 2 mm lead      | 1             |
| 250 mm lead screw with 2 mm pitch and 8 mm lead      | 1             |
| 1/4" x 8mm Flexible Coupling                         | 2             |
| 200 mm linear rod with 8 mm diameter                 | 2             |
| 2040 Aluminum Extrusion 1" Length                    | 1             |
| Nema 17 Stepper Motor                                | 1             |
| Arduino UNO                                          | 1             |
| A4988 Stepper Driver                                 | 1             |
| Small Breadboard                                     | 1             |
| Panel Mount Latching Push Buttons (On/Off)           | 1             |
| Panel Mount Momentary Push Buttons (On/Off)          | 1             |
| Limit Switch (On/Off)                                | 1             |
| RGB Common Cathode LED                               | 1             |
| Power Supply Quad Output (5V, 12V, 24V, 12V, 4 amp   | 1             |


<div style="display: flex; gap: 12px; flex-wrap: wrap;">
  <a href="/assets/img/Arduino Code.pdf" target="_blank"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;">
     View Arduino Code
  </a>

  <a href="/assets/img/Wiring diagram for the Arduino UNO.pdf
" target="_blank"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;">
     View Wiring Diagram
  </a>

  <a href="/assets/img/Dimensional Drawings.pdf
" target="_blank"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;">
     View Dimensioned Drawings
  </a>
</div>




 


