---
title: Humanoid Robotic Arm
layout: single
permalink: /projects/arm
toc: false
author_profile: true
header:
    teaser: /assets/images/arm.png
excerpt: "Also as part of Wisconsin Robotics, this project’s goal was mostly to move around, interact with people or objects, and look cool."
classes: wide
gallery:
  - image_path: /assets/images/arm-sketch-1.JPG
    alt: "sketch of spur gears for arm joint"
  - image_path: /assets/images/arm-sketch-2.jpg
    alt: "sketch of bevel gears for arm joint"
gallery-1:
  - image_path: /assets/images/arm.png
    alt: "CAD design of the second arm iteration"
  - image_path: /assets/images/arm-real.png
    alt: "Assembled arm, with a 3D printed motorized hand"
---
My first project with Wisconsin Robotics was a 3 degree of freedom humanoid arm, which we undertook with the goal of doing some simple manipulation tasks. I worked on the mechanical design of the joints, then wrote inverse kinematics algorithms in Python to run on a Raspberry Pi and PID control in C++ to run on an Arduino. The joint angles determined by the Pi were sent over USB to the Arduino, which ran feedback control loops to read and control the position of each joint using absolute encoders.

The first iteration was built almost entirely out of parts we salvaged from old projects, plus a couple 3D-printed bevel gears. Using bevel gears made it possible to mount the motor with its axis in line with the arm, occupying the space inside the arm cavity without making joints excessively wide and bulky. The joints were made of hand-drilled plywood, leading to some pretty bad tolerances, but the arm was functional enough to do a good job knocking things off a table.
{% include gallery id="gallery" caption="Initial design sketches of arm joint gearing." %}

After testing identified some major issues with backlash and broke a couple of parts, I spent time redesigning the joints to use laser cut HDF for better accuracy and turned new axles out of aluminum hex stock. Because the 3D printed gears were a little too soft to transmit enough torque to the axles, the new design has the gear bolted directly to the driven link. They're also now printed out of carbon fiber filled nylon filament for higher stiffness and better wear resistance.
{% include gallery id="gallery-1" caption="CAD design and finished assembly of the revised arm." %}