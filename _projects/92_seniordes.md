---
title: Mars Rover Drill
layout: single
permalink: /projects/seniordes
toc: false
author_profile: true
header:
    teaser: /assets/images/drill-brushless.jpg
excerpt: "For our capstone design project, some robotics teammates and I have been designing the soil extraction and testing capabilities for a competitive mock-Mars rover."
classes: wide
gallery:
  - image_path: /assets/images/drill-v1.jpg
    alt: "Early CAD prototype of auger and sheath"
  - image_path: /assets/images/drill-v1-sand.jpg
    alt: "Simple auger test"
  - image_path: /assets/images/drill-cad.jpg
    alt: "More recent CAD of the drill assembly"
  - image_path: /assets/images/drill-real.jpg
    alt: "Soil drill testing"
  - image_path: /assets/images/drill-side.jpg
    alt: "Front view of assembled drill"
  - image_path: /assets/images/drill-brushless.jpg
    alt: "Final drill with stronger brushless auger motor"

gallery1:
  - image_path: /assets/images/drill-diagram.png
    alt: "Diagram of connections between the science system and rover"
  - image_path: /assets/images/fluoro-carousel.jpg
    alt: "Full science system mounted on the underside of the rover"
---
The main project for Wisconsin Robotics—UW-Madison's competitive robotics team—is a scaled-down Mars rover that competes in the [University Rover Challenge](https://urc.marssociety.org/home){:target="_blank"}. Just like the real rovers, ours is required to extract and test subsurface regolith (loose rock and dust) samples and analyze them for signs of life. For our capstone design project, some robotics teammates and I took on the task of designing a soil drill and fluorometer to accomplish this portion of the mission. My primary responsibility was the mechanical design and testing of the drill, which includes the rotary auger to move soil and the insertion mechanism to drive the drill into the ground.

Literature on past rover and lander drills served as a starting point for motor selection and auger geometry. We ruled out rotary-percussive drilling (like is currently on Mars) pretty early because the competition didn't require us to drill into any rocks and we didn't think we could afford the increased complexity. From there I surveyed the drills used on previous missions for ones that had a similar depth and sample mass capabilities to draft our specs for drilling speed and motor power. 

{% include gallery id="gallery" caption="Progression of the drill design in CAD and prototypes" %}

![image-right](/assets/images/drill-labeled.jpg){: width="30%" .align-right}
The sheathed auger, insertion mechanism, and sample chute on the drill each went through 2-4 iterations of prototyping and testing in sand. We were fortunate to have access to 3D printers both through the school and the robotics team, which let us iterate pretty fast and work with materials like ASA, CF-Nylon, and TPU. I also got a lot of use out of laser cutting and waterjet cutting.

![image-left](/assets/images/fluoro-poster.png){: width="30%" .align-left}
During the second half of the project my focus shifted from design to integration onto the full rover, both physically and electrically. Our system relied on a combination of brushless motors for higher power or precision components and brushed motors for mostly fluid pumping, all of which had to be transitioned from our benchtop setup to the rover's onboard driver boards. During this phase I got very familiar with VESC tool, the configuration software for our motor drivers, and wrote some ROS2 nodes to connect our system to teleoperation and broadcast incoming data. We also worked with the client to establish a set of capabilities for a custom PCB that would read from the soil probes and fluorometer, as well as a ultraviolet spectrophotometer they had built for DNA detection. 

{% include gallery id="gallery1" caption="Planned functional diagram and physical mounting of the system" %}