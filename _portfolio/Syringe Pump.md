---
title: "Syringe Pump"
category: fabrication
layout: single
classes: wide
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
This prototype is a low-cost, motor-driven syringe pump designed to precisely dispense fluids at controlled flow rates using a stepper motor and lead screw mechanism. The system converts rotational motion into linear motion to advance or retract the syringe plunger while securely supporting both 10 mL and 20 mL syringes without the need for tools. An Arduino-based control system allows users to start, pause, manually jog, and adjust flow rates through onboard buttons, a potentiometer, and an LCD interface that provides real-time feedback. Safety and usability are enhanced through a limit switch that automatically stops the pump when the syringe is empty, color-coded LED status indicators, and protected electronics housed in a 3D-printed enclosure. Additionally, the prototype includes wireless remote control functionality using ESP32 microcontrollers, enabling additionally flexible and hands-free operation.

# Features of the design 
* **1.** Low-Cost, DIY Alternative to Commercial Syringe Pumps
This prototype demonstrates that a traditionally expensive medical and laboratory device can be recreated using affordable components such as 3D-printed parts, an Arduino, and stepper motor control. By meeting the same functional requirements as commercial pumps that cost hundreds to thousands of dollars, the design shows strong potential for cost-effective applications in educational, research, or low-resource settings.

* **2.** Dual Syringe Compatibility Without Tools
The pump is designed to accommodate both 10 mL and 20 mL syringes using dedicated mounting slots, allowing users to switch syringe sizes quickly without tools or reassembly. This improves usability and reduces setup time while maintaining proper support and preventing sagging during operation.

* **3.** Precise and Flexible Flow Rate Control
The use of a stepper motor with microstepping and a lead screw enables highly precise linear motion, resulting in accurate and repeatable flow rates. The system offers multiple control modes:
  * Preset flow rates for 10 mL and 20 mL syringes
  * Manual fast forward and reverse control
  * User-adjustable flow rates via a potentiometer
  * This flexibility makes the pump suitable for a wide range of applications.

* **4.** Comprehensive User Feedback and Safety Features

The prototype integrates LED status indicators, an LCD screen, and a limit switch, providing clear real-time feedback to the user. The system:
Automatically stops when the syringe is empty
Uses color-coded LEDs to indicate running, paused, and end-of-travel states
Displays system status, motion direction, syringe size, and speed on the LCD
These features enhance safety, usability, and reliability.

* **5.** Remote Control Capability and Expandable Electronics

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




 


