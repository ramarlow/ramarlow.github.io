---
title: Engineering Intern, Triton Medical Robotics
layout: single
permalink: /roles/triton23
toc: false
author_profile: true
header:
    teaser: /assets/images/triton.svg
excerpt: "[Triton](https://tritonrobotics.com/), a division of Neptune Medical, is working to make a robotically-controlled endoscope using Neptune's really cool [rigidizing technology](https://gipathfinder.com/technology/). I was lucky enough to work there over the summer of 2023, where I helped design and implement tests and equipment for use with flexible composite medical catheters."
classes: wide
gallery:
  - image_path: /assets/images/fixture-cad.png
    alt: "Rendering of a CAD model of the test fixture"
  - image_path: /assets/images/fixture-real.png
    alt: "Photo of the constructed test fixture"
---
While working at Triton, my biggest project was updating the test fixturing and methods used to measure and compare the stiffness of endoscopes. The main design goals were to avoid damaging the test samples, incorporate a water bath for submerged testing, and streamline data gathering and processing to enable faster design iteration. The new fixture has differently shaped jaws to reduce pinching damage, linear rails for repeatable positioning, and a tub to allow wet and dry testing. 
{% include gallery caption="The CAD model of the new fixture and the final result" %}
![image-right](/assets/images/fixture-stats.png){: width="50%" .align-right}
I designed the fixture in Solidworks, assembled it, then conducted trials and processed data in Python to verify its performance and reliability. This verification dataset was made of a bit over 2000 trials that I ran on both standard production and new prototype endoscopes. The data indicated that the new fixture had slightly increased noisiness in data, but faster setup and the ability to test in submerged environments were important enough improvements that the fixture was adopted into use.

![image-left](/assets/images/rigidizer.png){: width="30%" .align-left}
Another project I undertook at Triton was prototyping a handheld pressurized air supply for product demonstration purposes. The previous solution had relied on a 5-gallon air tank, which was impractical for off-site demonstrations and generally inconvenient for portability. After trying to solve this by sourcing a smaller tank, I further reduced the size and complexity by switching to compressed CO2 canisters, which are already commonly available for bike tire inflation, and designed a palm-sized enclosure for a small regulator and valve. In testing, I determined that the new device would supply enough air for at least 20 rigidization cycles, about 4 times what is usually used in demonstration.

![image-center](/assets/images/rigidizer-comparison.jpg){: .align-center}

Aside from these projects, I was responsible some other miscellaneous tasks. In working with other engineers to carry out component failure mode tests on new materials, I was able to gather observations and data that helped tune critical process parameters. I also referenced supplier datasheets to assemble and solder a few sensor arrays used for spatially locating the endoscopes.