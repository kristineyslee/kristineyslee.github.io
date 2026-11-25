---
title: "Wireless IMU Glove Mouse"
excerpt: "Encouragement Prize, SNU Mechatronics Contest, 2024"
collection: portfolio
header:
  teaser: airglove.jpg
---

**Award:** Encouragement Prize, SNU Mechatronics Contest — Department of Mechanical Engineering, Seoul National University (Jun. 2024)  
**Team:** 4 members, Mechatronics course project

Commercial air mice try to copy every function of a regular mouse, which makes them expensive and unintuitive. Most everyday laptop work, however, needs only a few actions: moving the cursor, clicking, scrolling, zooming, and switching windows. We built a low-cost glove that does exactly these with natural hand motions — an "air trackpad" that works without a desk surface.

**How it works**
* Two MPU-6050 IMU sensors on the fingers measure finger angles, read by an Arduino Pro Micro
* A Bluetooth module (HC-06) sends the commands to the computer wirelessly
* Buttons on a flexible finger pad handle left/right click, and trigger buttons switch between three gesture modes for functions such as scrolling, zooming, and switching windows
* A power button separates intentional gestures from everyday hand motion, with an LED showing the status

**What I did**
* Wrote the code that detects hand motion from the IMU data and turns it into mouse actions

**Results:** A working wireless prototype built for about ₩24,000 in parts.
