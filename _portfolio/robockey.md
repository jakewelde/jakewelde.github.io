---
title: "Robockey"
excerpt: "How can we stabilize a handheld camera during a long exposure automatically and in an ergonomic manner?"
author: Test
collection: portfolio
thumbnail: "/images/robockey.jpg"
year: 2016
gallery:
  - url: robockey/1.jpg
    image_path: robockey/1.jpg
  - url: robockey/2.jpg
    image_path: robockey/2.jpg
  - url: robockey/3.jpg
    image_path: robockey/3.jpg
  - url: robockey/5.jpg
    image_path: robockey/5.jpg
  - url: robockey/6.jpg
    image_path: robockey/6.jpg
  - url: robockey/8.jpg
    image_path: robockey/8.jpg
  - url: robockey/10.jpg
    image_path: robockey/10.jpg
  - url: robockey/19.jpg
    image_path: robockey/19.jpg
  - url: robockey/DSC_0761.jpeg
    image_path: robockey/DSC_0761.jpeg
---

Design of Mechatronic Systems, Fall 2016

*with Diego Caporale, Matt Oslin, and Garret Wenger*

![image-center](/images/robockey.jpg){: .align-center}

The final project of MEAM 510: Design of Mechatronic Systems - Robockey, a tournament in which teams of up to four students build three robots capable of playing hockey against each other completely autonomously. In this month-long race to the finish, each team was tasked with developing a system capable of localizing an infrared-emitting puck, providing odometry within the competition rink using a constellation of infrared stars tracked by a camera from a Wii remote, controlling the robot to pursue the puck and score, and pack enough pushing power and weight into the robot to maintain authority in the rink. Then – make two more of them before competition day. 

{% include gallery %}

Our robots were equipped with solenoid goal-shooting mechanisms and ultrasonic sensors to detect the presence of an opponent in their line of fire. A behavior state machine enabled robots to manage various goals depending on the state of the game, such as hysteretic offensive-defensive behavior switching for the goalie. 

We took first place on tournament day!


<iframe width="420" height="315" src="https://www.youtube.com/embed/MaSbL68Hj4A" frameborder="0" allowfullscreen></iframe>
