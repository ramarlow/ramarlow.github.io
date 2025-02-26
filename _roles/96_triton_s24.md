---
title: Triton Medical Robotics Internship
layout: single
permalink: /roles/triton24
toc: false
author_profile: true
header:
    teaser: /assets/images/triton.svg
excerpt: "I had a really fun time returning as an intern to [Triton](https://tritonrobotics.com/) in the summer of 2024. I rejoined the endoscopy team to improve and expand testing capabilities, support manufacturing and documentation efforts, and also wrote a tool for analyzing roslogs of robot telemetry."
classes: wide
gallery:
  - image_path: /assets/images/sphincter-fixture.jpg
    alt: "Sphincter fixture for simulated procedure testing"
  - image_path: /assets/images/mfg-cradle.jpg
    alt: "Manufacturing fixture to retain devices and prevent unconstrained movement"
gallery-1:
  - image_path: /assets/images/rigidizer-internals.jpg
    alt: "Fittings and regulator inside device"
  - image_path: /assets/images/rigidizer-shell.jpg
    alt: "Redesigned shell of the device"
---
Thanks to my previous experience at Triton, I was able to jump straight into many of my projects during this second internship. My first task was conducting device fatigue failure testing to evaluate different polymer layers for the endoscope body. This consisted not only of executing automated motor driving test scripts and recording results, but also of doubling our testing capacity by building a second set of test fixtures so units could be run on multiple capital robots simultaneously. 

After the initial couple weeks of design sprint yielded a successful construction, I continued working with the fixtures to make some design changes based on my experiences as a user. Later on in the leadup to V&V testing I also reran the testing procedures on a new software release to find and report bugs, some of which had the potential to accidentally destroy devices or damage equipment. 

As a part of the endoscopy team, I contributed to a major push toward improving manufacturing capabilities by drafting and revising process instructions, building fixutres to make assembly less error-prone, and investigating failed units to improve yield. I conducted stackup analyses of the endoscope assembly to set length specifications for several custom parts, then pulled statistics from historical manufacturing records to set an achievable tolerance and estimate its impacts on our part yield. Based on assembler requests, I also designed and installed a few fixtures to help manage unwieldy long parts in the cleanroom and supported bringup of some high-demand equipment so processes could run in parallel more easily.
{% include gallery caption="Fixtures designed for device testing and manufacturing" %}

My longest-term project this time was expanding on a python notebook used to analyze rosbags collected from the robot during driving. A lot of meaningful characteristics like motor usage and steer cable forces could be used to form an image of what typical device use looked like, which in turn made our testing protocols more representative and meaningful. I refactored the majority of the code so it was easier to add a new statistic, plot findings, and filter out idle time in which the robot was recording while stationary. I also sped up load times, increasing the number of runs that could be tabulated at once from around 5 to over 20. This came at a time during which a lot of new data was coming in, so being able to process it with less effort and need for troubleshooting made it much easier to build up these useful datasets.

The last small side-project that I worked on was improving on my compact rigidizing device from the previous summer's internship. I was happy to learn that a few copies of my prototype had been made to fill demands, but also learned that assembling them had been "a real pain" due to inconsistencies between fittings causing alignment issues. I addressed these complaints by redesigning the inner geometry of the cosmetic shell to accomodate more angular error and reduce weight overall, then printed and assembled a few more units and more fully documented the process so it wouldn't be as bad in the future.
{% include gallery-1 caption="Images of the handheld rigidizer showing the internal fittings and new casing" %}