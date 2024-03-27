---
title: Go Playing Robot
layout: single
permalink: /projects/go-robot
toc: false
author_profile: true
header:
    teaser: /assets/images/go_robot.jpg
excerpt: "As our Intro to Robotics final project, I worked with two classmates to build attachments and write control code allowing an off-the-shelf robotic arm to play the board game Go."
classes: wide
---
For the final project of the Introduction to Robotics course, our team of 3 decided to build a robot to play the board game Go. We started from a provided off-the-shelf 6-DoF robotic arm, which we suspended from a gantry to open up more of its workspace. I modified the arm by attaching another servo to the tip and adding an electromagnet to pick up the game pieces, which we made custom with ferromagnetic cores. I also wrote inverse kinematics, motion planning, and joint control nodes in the ROS Noetic framework, while another group member wrote a computer vision node to perceive the board and attempted to write a Go engine, which ended up being more difficult than expected.