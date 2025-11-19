---
title: Hello
layout: splash
permalink: /
header:
    #overlay_color: "#cc5500"
    overlay_filter: rgba(204, 85, 0, 0.6)
    overlay_image: /assets/images/potato_bw.jpg
    actions:
        - label: "My Resume"
          url: "resume"
        - label: "LinkedIn"
          url: "https://www.linkedin.com/in/robert-marlow-301779222/"
excerpt: "I'm Robert, a mechanical engineering MS student at UCLA. I'm interested in all sorts of robotics, wearable devices, controls, and origami. These are some of my past experiences and projects."
feature_row_0:
  - image_path: /assets/images/triton-logo-rev.svg
    image_caption: "Summer 2024"
    title: "2024 Triton Robotics Internship"
    excerpt: "I had a really fun time returning to [Triton](https://tritonrobotics.com/) in the summer of 2024 as an intern. I rejoined the endoscopy team to do a bunch of device durability testing, improve and expand testing capabilities, support manufacturing and documentation efforts, and also wrote a tool for analyzing roslogs of robot telemetry."
    url: "/roles/triton24"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/triton.svg
    image_caption: "Summer 2023"
    title: "2023 Triton Robotics Internship"
    excerpt: "[Triton](https://tritonrobotics.com/), a division of Neptune Medical, is working to make a robotically-controlled endoscope using Neptune's really cool [rigidizing technology](https://gipathfinder.com/technology/). I was lucky enough to work there over the summer of 2023, where I helped design and implement tests and equipment for use with flexible composite medical catheters."
    url: "/roles/triton23"
    btn_label: "Read More"
    btn_class: "btn--warning"
feature_row_1:
  - image_path: /assets/images/drill-cad.jpg
    image_caption: "Fall 2024-Spring 2025"
    title: "Mars Rover Drill"
    excerpt: "For our capstone design project, some robotics teammates and I have been designing the soil extraction and testing capabilities for a competitive mock-Mars rover."
    url: "/projects/seniordes"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/weeblebot.jpg
    image_caption: "Spring 2024-2025"
    title: "Weeblebot"
    excerpt: "I worked with a group of fellow undergrads in the BADGER Lab on the ongoing weeblebot project, a two-wheeled robot that balances passively from its unique drivetrain geometry."
    url: "/projects/weeblebot"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/battlebot.png
    image_caption: "Spring 2023-2024"
    title: "Mini Battlebots"
    excerpt: "As part of Wisconsin Robotics, the Outreach/Minibots subteam is working to make a set of child-safe nonlethal battlebots that engage in “sparring” by whacking each other with plastic squeaky hammers."
    url: "/projects/battlebots"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/arm.png
    image_caption: "Fall 2021-2022"
    title: "Humanoid Robotic Arm"
    excerpt: "Also as part of Wisconsin Robotics, this project's goal was mostly to move around, interact with people or objects, and look cool."
    url: "/projects/arm"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/signal.jpg
    image_caption: "Fall 2021-2023"
    title: "Turn Signal Light"
    excerpt: "This project was originally the product of a semester-long design prompt to make something interesting using a microcontroller. It consists of some LEDs stuck to my hand that I can light up in different patterns to signal turns when bicycling at night."
    url: "/projects/signal"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/go-robot.jpg
    image_caption: "Fall 2023"
    title: "Go Playing Robot"
    excerpt: "As our Intro to Robotics final project, I worked with two classmates to build attachments and write control code allowing an off-the-shelf robotic arm to play the board game Go."
    url: "/projects/go-robot"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/trolley.jpg
    image_caption: "Fall 2021"
    title: "Autonomous Trolley"
    excerpt: "The Intro to Mechanical Engineering course focused around building an obstacle-avoiding trolley using an Arduino and custom gearbox, and custom lightweight chassis."
    url: "/projects/trolley"
    btn_label: "Read More"
    btn_class: "btn--warning"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_0" type="left" %}

{% include feature_row id="feature_row_1" %}
