---
title: Turn Signal Light
layout: single
permalink: /projects/signal
toc: false
author_profile: true
header:
    teaser: /assets/images/signal.jpg
excerpt: "This project was originally the product of a semester-long design prompt to make something interesting using a microcontroller. It consists of some LEDs stuck to my hand that I can light up in different patterns to signal turns when bicycling at night."
classes: wide
gallery:
  - image_path: /assets/images/signal-parts.png
    alt: "CAD renderings of 3D printed parts"
  - image_path: /assets/images/signal.jpg
    alt: "Photo of the assembled turn signal glove"
gallery-1:
  - image_path: /assets/images/kicad-layout.png
    alt: "Circuit layout in KiCAD"
  - image_path: /assets/images/signal-pcb.png
    alt: "Fabricated PCB"
---
This project was originally the product of a semester-long design prompt by UW MadMakers to make something interesting using a microcontroller. I designed a circuit and wrote code to interface an Arduino Nano with an Inertial Measurement Unit and some small LEDs, then soldered the circuit and designed parts to fit it into a glove. I decided to use surface mount LEDs for their small form factor, but hand soldering them to loose wires was challenging and resulted in a lot of burns. To cover up my mistakes and improve mechanical strength, I resin printed some clear diffusers that held the LEDs together.
{% include gallery caption="Parts designed for the signal and the assembled glove" %}

The IMU was used to detect the orientation of my hand when signaling a turn, then blink lights pointing in whatever direction I wanted to go. My goal was to make turn signals more visible at night, since I had been biking a lot more after dark. The concept was inspired partially by existing gloves that do this without sensing orientation, and partially by a helmet I have that includes built-in turn signals, but requires a remote that I always forget to carry. 

One of the electrical connections broke after riding with it for a while, so instead of fixing it I decided to make a second version. I've replaced the loose wires with a custom PCB and swapped the microcontroller to a bluetooth capable module, which I’m hoping will let me use the glove to spoof the signal from the NRF BLE chip in my helmet’s remote. So far, this has been a fun opportunity to learn PCB design and surface mount soldering, and will hopefully be fully assembled sometime this year.
{% include gallery id="gallery-1" caption="Board design in software and after fabrication" %}