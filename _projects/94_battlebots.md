---
title: Mini Battlebots
layout: single
permalink: /projects/battlebots
toc: false
author_profile: true
header:
    teaser: /assets/images/battlebot.png
excerpt: "As part of Wisconsin Robotics, the Outreach/Minibots subteam is working to make a set of child-safe nonlethal battlebots that engage in “sparring” by whacking each other with plastic squeaky hammers."
classes: wide
gallery:
  - image_path: /assets/images/battlebot-wiring.jpg
    alt: "Messy wiring of various electrical components that necessitated a PCB"
  - image_path: /assets/images/battlebot-pcb.jpg
    alt: "Custom motor and power PCB that I helped a new member design and assemble"
  - image_path: /assets/images/battlebot.png
    alt: "The battlebots with their new ladybug facades"
---
![image-right](/assets/images/chassis-v1-cad.png){: width="30%" .align-right}
As part of Wisconsin Robotics, in an attempt to appease all the kids who want to break our robots (including some team members), our most recent project is a set of nonlethal battlebots that engage in “sparring” by whacking each other with plastic squeaky hammers. I designed the drive train parts for the first iteration of the chassis, which was modeled on the dimensions of one of our old projects and fabricated using laser cut HDF. The robots would hit each other on their acrylic lids, which were mounted on limit switches to detect successful hits. 

As subteam lead since then, I’ve tried to delegate much of the work, especially on the mechanical and software sides, to new members so they can develop skills. My most direct involvement has been guiding members through the process of designing a PCB to carry our ESP32 microcontrollers, connecting them to power supply circuitry and motor drivers. This should solve a lot of wire management and shorting issues once we solder and install the boards. Other members of the team have redesigned the chassis to make it less boxy by adding a ladybug-shaped shell, which has made them even more popular at our outreach events.
{% include gallery caption="Battlebot progress, including circular chassis, new PCB, and ladybug facades" %}