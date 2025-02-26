---
title: Weeblebot
layout: single
permalink: /projects/weeblebot
toc: false
author_profile: true
header:
    teaser: /assets/images/weeblebot.jpg
excerpt: "I worked with a group of fellow undergrads in the BADGER Lab on the ongoing weeblebot project, a two-wheeled robot that balances passively from its unique drivetrain geometry."
classes: wide
---
My first goal with Weeblebot was to resolve a versioning conflict between our Raspberry Pi (running Debian Buster to support ROS Noetic) and an incompatible Pi Camera v2, which would only work on a more recent Debian version. An attempt to upgrade the Debian version had broken the ROS installation, so I learned how to implement a Docker container for ROS to run inside.

![image-right](/assets/images/weeblebot.jpg){: width="30%" .align-right}
After getting the robot moving, I found that our existing method of manually inputting motor speeds made it hard to achieve any level of precise driving. To make the robot more interactive and help us test the atypical system dynamics, I wrote several ROS nodes to take live motor speed inputs from an off-the-shelf gamepad. This change made it possible to exhibit the robot at Engineering Expo, a community STEM event where lab groups and student clubs share their work with visiting school groups. Driving at this event helped us uncover a big stability issue when spinning too fast, which we plan to incorporate into our controls moving forward.