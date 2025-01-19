---
title: Weeblebot
layout: single
permalink: /projects/weeblebot
toc: false
author_profile: true
header:
    teaser: /assets/images/weeblebot.png
excerpt: "I worked with a group of fellow undergrads in the BADGER Lab on the ongoing weeblebot project, a two-wheeled robot that balances passively from its unique drivetrain geometry."
classes: wide
---
My first goal with weeblebot was to resolve a versioning conflict between our Raspberry Pi (running Debian Buster to support ROS Noetic) and an incompatible Pi Camera v2, which would only work on a more recent Debian version. An attempt to upgrade the Debian version had broken the ROS installation, so I learned how to implement a Docker container for ROS to run inside.