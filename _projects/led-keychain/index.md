---
layout: post
title: LED Keychain
description:  For HyTech Racing new member onboarding, I designed the components and PCB for a flashing LED keychain in Altium Designer, then sent the design for manufacturing and soldered the physical board.
skills: 
- PCB Design
- Component Design
- Soldering
- Altium Designer 
main-image: /keychain-front.jpg 
---

---
# Goal
To make a keychain in the shape of the HyTech logo that can be connected to a USB-C power source and flash 6 LED lights on a 53% duty cycle. The circuit models the Ready-To-Move light used on the car to indicate that high voltage power is connected to the motors. 
## Background/Introduction
Starting this project, I had little experience with PCB design, reading datasheets, soldering, and none at all with Altium Designer. Throughout the project, I learned a lot about the process of designing PCBs, parsing datasheets, and using Altium, to the point where I can comfortably work with these tools and complete similar tasks on my own. 
## Designing LM555 Timer Component/Footprint
{% include image-gallery.html images="timer.png" height="400" %}
{% include image-gallery.html images="timer-footprint.png" height="400" %}
## Designing Timer/LED and USB-C Port Schematics
{% include image-gallery.html images="timer-led.png" height="400" %}
{% include image-gallery.html images="usb-c.png" height="400" %}
## Creating PCB Shape/Design
{% include image-gallery.html images="pcb-shape.png" height="400" %}
## Placing and Routing Components
{% include image-gallery.html images="traces-back.png" height="400" %}
{% include image-gallery.html images="pcb-back.jpg" height="400" %}
{% include image-gallery.html images="pcb-front.jpg" height="400" %}
## Soldering the Final PCB
{% include image-gallery.html images="soldered.jpg" height="400" %}
