---
title: Hello
layout: splash
permalink: /
#header:
#    overlay_color: "#cc5500"
#    actions:
#        - label: "Résumé"
#          url: "https://ramarlow.github.io/resume"
intro:
  - excerpt: #"\nHello, I'm Robert. I'm currently a mechanical engineering undergrad at UW-Madison."
feature_row_0:
  - image_path: /assets/images/triton.svg
    image_caption: "Summer 2023"
    title: "Triton Robotics Internship"
    excerpt: "[Triton](https://tritonrobotics.com/), a division of Neptune Medical, is working to make a robotically-controlled endoscope using Neptune's really cool [rigidizing technology](https://gipathfinder.com/technology/). I was lucky enough to help out there over the summer of 2023, and helped design and implement tests and equipment for use with flexible composite medical catheters."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
feature_row_1:
  - image_path: /assets/images/battlebot.png
    image_caption: "Spring 2023-2024"
    title: "Mini Battlebots"
    excerpt: "As part of Wisconsin Robotics, the Outreach/Minibots subteam is working to make a set of child-safe nonlethal battlebots that engage in “sparring” by whacking each other with plastic squeaky hammers. "
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/arm.png
    image_caption: "Fall 2021-2022"
    title: "Humanoid Robotic Arm"
    excerpt: "Also as part of Wisconsin Robotics, this project's goal was mostly to move around, interact with people or objects, and look cool."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
feature_row_2:
  - image_path: /assets/images/signal.jpg
    image_caption: "Fall 2021-2023"
    title: "Turn Signal Light"
    excerpt: "This project was originally the product of a semester-long design prompt to make something interesting using a microcontroller. It consists of some LEDs stuck to my hand that I can light up in different patterns to signal turns when bicycling at night."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/go_robot.jpg
    image_caption: "Fall 2023"
    title: "Go Playing Robot"
    excerpt: "As our Intro to Robotics final project, I worked with two classmates to build attachments and write control code allowing an off-the-shelf robotic arm to play the board game Go."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
  - image_path: /assets/images/trolley.jpg
    image_caption: "Fall 2021"
    title: "Autonomous Trolley"
    excerpt: "The Intro to Mechanical Engineering course focused around building an obstacle-avoiding trolley using an Arduino and custom gearbox."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--warning"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_0" type="left" %}

{% include feature_row id="feature_row_1" %}

{% include feature_row id="feature_row_2" %}
