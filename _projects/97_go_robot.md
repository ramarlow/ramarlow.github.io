---
title: Go Playing Robot
layout: single
permalink: /projects/go-robot
toc: false
author_profile: true
header:
    teaser: /assets/images/go-robot.jpg
excerpt: "As our Intro to Robotics final project, I worked with two classmates to build attachments and write control code allowing an off-the-shelf robotic arm to play the board game Go."
classes: wide
---
For the final project of the Introduction to Robotics course, our team of 3 decided to build a robot to play the board game Go. This was largely inpired by a shared enjoyment of board games, though none of us knew how to play Go specifically before starting. We had initially considered playing chess, but too many other groups had the same idea and grasping Go pieces seemed more predictable.

![image-left](/assets/images/arm-gantry.png){: width="30%" .align-left}
We started from a provided off-the-shelf 6-DoF robotic arm, which we suspended from a gantry to open up more of its workspace by allowing the robot to extend both forward and backward. The robot's joint arrangement meant that even though it could theoretically reach plenty far, doing so while keeping control of end effector orientation wasn't possible. 

![image-right](/assets/images/electromagnet.png){: width="30%" .align-right}
I modified the arm by attaching another servo to the tip and adding an electromagnet to pick up the game pieces, which we custom made with ferromagnetic cores. Although the arm originally had a gripper, it wouldn't have been precise or small enough to pick up game pieces without disturbing the board state. The electromagnet gave us a bit of wiggle room when picking up pieces, which ended up being a big help.

![image-left](/assets/images/go-cv.png){: width="30%" .align-left}
I also wrote inverse kinematics, motion planning, and joint control nodes in the ROS Noetic framework. We simplified inverse kinematics math by locking some joints in place, then further reduced the degrees of freedom by solving the wrist separately from the rest of the arm. Another group member wrote a computer vision node to perceive the board and attempted to write a Go engine, which ended up being more difficult than expected. 

![image-center](/assets/images/rqt-graph.png){: .align-center}

Since none of us had extensive experience on the electrical engineering side, I handled wiring of the e-stop, electromagnet, additional servo, and interaction buttons connected to the Raspberry Pi, then implemented them by writing ROS nodes.