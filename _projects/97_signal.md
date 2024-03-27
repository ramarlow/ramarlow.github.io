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
---
This project was originally the product of a semester-long design prompt by UW MadMakers to make something interesting using a microcontroller. I designed a circuit and wrote code to interface an Arduino Nano with an Inertial Measurement Unit and some small LEDs, then soldered the circuit and designed parts to fit it into a glove. The IMU was used to detect the orientation of my hand when signaling a turn, then blink lights pointing in whatever direction I wanted to go.  My goal was to make turn signals more visible at night, and the concept was partially inspired by existing gloves that do this without sensing orientation and a helmet I have that includes built-in turn signals but requires a remote that I always forget to carry. One of the electrical connections broke after riding with it for a while, so instead of fixing it I decided to make a second, version replacing the loose wires with a custom PCB and swapping the microcontroller to a bluetooth enabled model, which I’m hoping will let me use the glove to spoof the signal from my helmet’s remote. This has been a fun opportunity to learn PCB design and surface mount soldering, and will hopefully be fully assembled sometime this year.