---
title: "MEAM 520: Introduction to Robotics"
collection: teaching
role: Head TA for Prof. Cynthia Sung and Prof. M. Ani Hsieh
type: "Graduate course with some advanced undergrads"
permalink: /teaching/meam520
venue: "University of Pennsylvania"
semester: "Fall 2020 and Fall 2021"
# location: "City, Country"
gallery:
  - url: meam520/score_1.png
    image_path: meam520/score_1.png
  - url: meam520/score_2.png
    image_path: meam520/score_2.png
  - url: meam520/score_3.png
    image_path: meam520/score_3.png
---

MEAM 520 is an introductory masters-level course taken by many first-semester robotics masters students and some advanced undergrads, spanning the mechanical, electrical, and computer science programs. Students arrive with a wide range of skills and prior experience. 

{% include figure image_path="/images/meam520/franka_block.jpg" caption="Students experimentally validate their algorithms on a Franka Emika Panda arm." %}

As a Head TA for two semesters, my role in the teaching team included adapting and developing laboratory assignments, working directly with students in office hours and lab to help them overcome their conceptual roadblocks or implementation challenges, and the design of a new hands-on final project for the course. I am very grateful that both professors for whom I TA'd (Cynthia Sung and Ani Hsieh) granted me significant opportunity to take part in the design of the laboratory assignments and the student learning experience. The other Head TA's Shane Rozen-Levy, Torrie Edwards, Xu Liu and the many masters TA's were all outstanding and reliable colleagues who each took on a vital portion of the course responsibilities.


Course Overview
==========================

GRASP's Justin Nachea put together a great video overview of the course:

<iframe width="420" height="315" src="https://www.youtube.com/embed/iH8EArj3w5A" frameborder="0" allowfullscreen></iframe>

Because one course can't introduce students to *all* areas of robotics in a single semester, MEAM 520 targets essential skill areas that are central to the development of any robotic system, with the following expected learning outcomes:

## 1. Understanding Geometry in Motion

Robotics is a physical discipline, requiring both the description and prescription of the motion of bodies through space. Students develop computational skills and intuition by studying forward, inverse, and differential kinematics of manipulator arms, resolving redundancy and planning collision-free motions to achieve manipulation goals. The pairing of core mathematical concepts with hands-on exercises conveys the power of theoretical tools to solve practical problems.

## 2. Implementing Software for Complex Robotic Systems

For many students, MEAM 520 is their first experience taking challenging algorithmic and mathematical concepts and implement them in software. Students discover the vital importance of a methodical approach to testing and evaluation and the limited scope and assumptions of an engineering solution. Perhaps the most significant learning outcome is the ability to communicate with other engineers about what's working and what's not, developing a plan to isolate the problem and bridge that gap.

## 3. Simulation to Reality Workflow

Working with real robots can be dangerous, difficult, and expensive, and lab time is limited in a large course with many students. For this reason, MEAM 520 provides a simulated lab environment leveraging standard robotics research tools like ROS and Gazebo. Students learn to prototype their solutions in simulation before coming in to work in the lab. They also learn to reason about the gap between reality and simulation at varying levels of fidelity.

{% include figure image_path="/images/meam520/franka_geometry.png" caption="Students used the manipulator geometry to model the position, orientation, and velocities of the end effector as a function of the joint states, and then leveraged their model to achieve manipulation goals." %}

My Teaching Role
================

## Fall 2020: A Virtual Robotics Laboratory  

I first TA'd for this course under Prof. Cynthia Sung during Fall 2020, when the pandemic necessitated virtual instruction. To create a vibrant learning experience despite the inability to work in the lab, we adapted the existing laboratory exercises to a simulated lab environment in which students could control a virtual robot to avoid obstacles and manipulate objects. Our efforts were featured in Penn Engineering Today: [Virtual Robots: Taking Risks in an Online Classroom](https://blog.seas.upenn.edu/virtual-robots-taking-risks-in-an-online-classroom/).

{% include figure image_path="/images/meam520/lynx_simulator.png" caption="Two Lynx arms go head-to-head in a livestreamed virtual Pick and Place Challenge." %}

We also introduced a final project tournament as an exciting opportunity for students to showcase and build upon the skills they gained during the semester. I led the design of the game rules for a "Pick and Place Challenge", in which two robot arms go head-to-head to each stack stationary and moving blocks in the environment into their tower. The scoring system rewarded the dexterity and precision enabled by students' new mastery of planning and kinematics and required handling randomly placed blocks in the environment.

{% include gallery 
 caption="Moving (dynamic) blocks are worth more than stationary (static) blocks, and blocks get more points the higher they are off the goal platform. Bonus points are granted if the designated (white) side of the block is facing upwards." 
 %}

## Fall 2021: Industrial Robot Hardware

The next semester, at the request of Prof. Ani Hsieh, the department invested in two Franka Emika Panda arms for the course, a drastic improvement over the hobby-grade Lynxmotion arms previously used. The move to a redundant 7-DOF manipulator required the development of a new inverse kinematics lab assignment that asked students to resolve this redundancy, which I spearheaded. The move to higher-performing manipulators also enabled a much more impressive [final demo](https://www.youtube.com/watch?v=kSxYnSfTZAQ), largely thanks to the integration efforts of other Head TA's Torrie Edwards and Xu Liu. Shane and I both received the Outstanding TA Award in the Mechanical Engineering department for our instruction in the course this semester.


<iframe width="420" height="315" src="https://www.youtube.com/embed/0o74lGcMhaA" frameborder="0" allowfullscreen></iframe>

Although I'm no longer a TA for MEAM 520, several years later the Pick and Place Challenge I designed is still the capstone of the course! Subsequent teaching teams have made improvements like the introduction of a real-world perception system to localize the scoreable blocks.

{% include figure image_path="/images/meam520/MEAM520 Poster.png" caption="The final tournament was open to the whole engineering community and it was a lot of fun to watch!" %}
