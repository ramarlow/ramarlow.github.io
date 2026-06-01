---
title: Powered Shopping Cart
layout: single
permalink: /projects/cart
toc: false
author_profile: true
header:
    teaser: /assets/images/cart-bucky.jpg
excerpt: "A teammate and I thought it'd be fun to build our own take on a classic William Osman video by attaching hoverboard hub motors to a (legally acquired) shopping cart."
classes: wide
gallery:
  - image_path: /assets/images/cart-wheel-cad.jpg
    alt: "CAD design of extender bracket"
  - image_path: /assets/images/cart-wheel.jpg
    alt: "Assembled extender bracket"
  - image_path: /assets/images/cart-wheel2.jpg
    alt: "Assembled extender bracket top view"
---
![image-right](/assets/images/cart-motor.jpg){: width="30%" .align-right}
A teammate and I thought it'd be fun to build our own take on [a classic William Osman video](https://youtu.be/5mcqKcdu2uM?si=rJ-Pm9tAt6rOvRYy){:target="_blank"} by attaching hoverboard hub motors to a (legally acquired) shopping cart. After talking about it for a couple months the ball really started rolling when I was able to find a used hoverboard on craigslist for free. From there we were able to get everything working using mostly leftover parts from other projects in just a couple weeks. The ODrive S1 motor controllers we used had originally been intended for use on the rover but their behavior under voltage sag and limited control options meant they were no longer needed, and they ended up being pretty well suited to the cart.

One of the few ways in which we deviated from the original video was in attaching the wheels to the cart. While Osman et al. tried to drill the existing holes on the cart bigger to fit the hoverboard axles, the video showed that they had a lot of difficulties with it, so I instead designed a simple extender bracket that we could cut out of aluminum sheet stock.

{% include gallery caption="A few images of the axle adapter thing" %}

We hooked everything up to a relatively inexpensive RC receiver and tested by driving the cart through the halls, then eventually outside on the street when we realized how many tire marks it was leaving. 

![image-center](/assets/images/cart-bucky.jpg){: .align-center}