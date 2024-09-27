---
layout: post
title: "Force Feedback Wheel Torque Upgrade"
author: "Whitman Hall"
categories: documentation
tags: [documentation]
image: DFGTwithmotor.jpg
---

The inspiration for this project stemmed from my dissatisfaction with the strength and force feedback quality of this Logitech force feedback steering wheel. The original motor and power MOSFETs were rated for 3 amps, while the power supply provided only 0.75 amps. To enhance performance, I upgraded the controller with a more powerful motor featuring increased holding torque, power MOSFETs with superior heat dissipation and 8-amp ratings, and a 6-amp power supply with over-current protection. These upgrades resulted in significantly improved force feedback responsiveness, greater torque, and cooler-running power chips compared to the original configuration.

## Building Timeline
![](/assets/img/DFGTwithmotor.jpg)
*The game wheel with old motor removed and more powerful motor installed*

![](/assets/img/DFGToldmotor.jpg)
*The original motor removed from the wheel*

![](/assets/img/DFGTgearscloseup.jpg)
*Gear view showing 3D printed motor gear and motor spacer*

![](/assets/img/DFGTBoard.jpg)
*Motherboard from wheel with new motor MOSFET power chips below*

![](/assets/img/DFGToldchips.jpg)
*Close up view of original MOSFET power chips rated for 3 Amps*

![](/assets/img/DFGTnewchip.jpg)
*One of the new upgrade MOSFET power chips rated for 8 Amps*

![](/assets/img/DFGTnewchips.jpg)
*New upgrade power chips soldered to board*

![](/assets/img/DFGTjumperwire.jpg)
*Close up of jumper wire and modified trace used to reroute FET drain so MOSFET feet don’t short out the motor*

![](/assets/img/DFGTcuttrace.jpg)
*Close up of cut trace to prevent left FET drain from running under chip and connecting to right FET drain foot*

![](/assets/img/DFGT.jpg)
*The finished gaming wheel with new chips and motor*
