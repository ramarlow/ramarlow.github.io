---
title: Autonomous Trolley
layout: single
permalink: /projects/trolley
toc: false
author_profile: true
header:
    teaser: /assets/images/trolley.jpg
excerpt: "The Intro to Mechanical Engineering course focused around building an obstacle-avoiding trolley using an Arduino and custom gearbox, and custom lightweight chassis."
classes: wide
---
The Intro to Mechanical Engineering course focused around building an obstacle-avoiding trolley using an Arduino and custom gearbox. Our group of 3 was worried about frictional losses in a multi-stage gearbox, so we opted for a single stage gearing with the pinion on the motor and the driven gear mounted directly on the wheel. Because one grading criteria was the trolley's ability to climb up a slope, we reduced component weight by strategically removing material from less crucial regions.

On the sensing side, the trolley took repeated distance measurements using an ultrasonic sensor and adjusted its speed to maintain a safe following distance with an erratically driving lead vehicle. We found that our readings had extreme noise whenever the motors were connected to power, which I mitigated by separating the logic and drive circuits using an optocoupler, then further smoothed by implementing a circular buffer and moving average of readings in our C++ code. These solutions were mostly successful and increased reliability quite a bit.

