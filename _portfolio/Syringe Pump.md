---
title: "Syringe Pump"
layout: single
classes: wide
author_profile: false
sidebar:
  nav: false

category: fabrication
excerpt: "Syringe Pump with interchangeable 5mL, 10mL, and 20mL syringes"

header:
  image: /assets/img/linear rod actuator final assembly.png
  teaser: /assets/img/linear rod actuator final assembly.png

gallery:
  - url: /assets/img/syringe pump finished assembly.png
    image_path: /assets/img/syringe pump finished assembly.png
    alt: "Finished assembly"
  - url: /assets/img/side by side syringe hold.jpg
    image_path: /assets/img/side by side syringe hold.jpg
    alt: "Side by side syringe holder"
  - url: /assets/img/remote controller box print pic.jpg
    image_path: /assets/img/remote controller box print pic.jpg
    alt: "Remote controller box"
---

  

# Description of the prototype
This low-cost, motor-driven syringe pump precisely dispenses fluids using a stepper motor and lead screw mechanism. It supports 10 mL and 20 mL syringes without tools and converts rotational motion into linear plunger movement. An Arduino-based system allows users to start, pause, manually jog, and adjust flow rates via buttons, a potentiometer, and an LCD for real-time feedback. Safety features include a limit switch, color-coded LEDs, and a 3D-printed protective enclosure. Wireless control via ESP32 microcontrollers enables hands-free operation.

# Features of the design 
* **Low-Cost, DIY Alternative to Commercial Syringe Pumps.**
This prototype demonstrates that a traditionally expensive medical and laboratory device can be recreated using affordable components such as 3D-printed parts, an Arduino, and stepper motor control. By meeting the same functional requirements as commercial pumps that cost hundreds to thousands of dollars, the design shows strong potential for cost-effective applications in educational, research, or low-resource settings.

* **Dual Syringe Compatibility Without Tools.**
The pump is designed to accommodate both 10 mL and 20 mL syringes using dedicated mounting slots, allowing users to switch syringe sizes quickly without tools or reassembly. This improves usability and reduces setup time while maintaining proper support and preventing sagging during operation.

* **Precise and Flexible Flow Rate Control.**
The use of a stepper motor with microstepping and a lead screw enables highly precise linear motion, resulting in accurate and repeatable flow rates. The system offers multiple control modes:
  * Preset flow rates for 10 mL and 20 mL syringes
  * Manual fast forward and reverse control
  * User-adjustable flow rates via a potentiometer
  * This flexibility makes the pump suitable for a wide range of applications.

* Comprehensive User Feedback and Safety Features

The prototype integrates LED status indicators, an LCD screen, and a limit switch, providing clear real-time feedback to the user. The system:
Automatically stops when the syringe is empty
Uses color-coded LEDs to indicate running, paused, and end-of-travel states
Displays system status, motion direction, syringe size, and speed on the LCD
These features enhance safety, usability, and reliability.

* Remote Control Capability and Expandable Electronics

A notable advanced feature is the wireless remote start/pause functionality using ESP32 microcontrollers and ESP-NOW communication. This allows operation from up to 150 meters away, which is uncommon in basic syringe pump designs. The modular electronics enclosure and non-permanent fasteners also make the system easy to maintain, modify, and expand in future iterations.


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
| Power Supply Quad Output (5V, 12V, 24V, 12V, 4 amp)  | 1             |

<h2>Table with 3D printed parts</h2>

| Part                                                 | Quantity      |
|------------------------------------------------------|---------------|
| Carriage                                             | 1             |
| End Support                                          | 1             |
| Enclosure Body                                       | 1             |
| Enclosure Lid                                        | 1             |
| Remote Box                                           | 1             |
| Remote Box Lid                                       | 1             |




<div style="display: flex; gap: 12px; flex-wrap: wrap;">
  <a href="/syringe-pump-code/arduino_code_for_syringe.ino"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;"
     download>
     Download Arduino Code
  </a>
</div>

  <a href="/assets/img/Wiring diagram for the Arduino UNO.pdf
" target="_blank"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;">
     View Wiring Diagram
  </a>
</div>

  <a href="/assets/img/Dimensional Drawings.pdf
" target="_blank"
     style="padding:10px 20px; background-color:#808080; color:white; text-decoration:none; border-radius:5px;">
     View Dimensioned Drawings
  </a>
</div>




 


