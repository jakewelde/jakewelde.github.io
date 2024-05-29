---
short_title: "Aerial Manipulation"
title: "Task Space Planning for Underactuated Aerial Manipulators"
excerpt: "How can we plan?"
collection: portfolio
thumbnail: "/images/pick_and_place.png"
year: 2021
publications:
  - key: Welde2020
  - key: Welde2021
redirect_from: 
  - /icra2020
  - /ral2021
---

2021

*with James Paulos and Vijay Kumar*

{% include figure image_path="/images/pick_and_place.png" caption="A simulated aerial manipulator, consisting of a quadrotor equipped with a 2-DoF manipulator arm, performs a 6-DoF manipulation task precisely, by jointly leveraging the actuators in the arm and in the vehicle while respecting the underactuation constraints of the combined system." %}

In this work, we address the problem of planning dynamically feasible trajectories for underactuated aerial manipulators to achieve a desired trajectory for the end effector. We consider a quadrotor equipped with an arbitrary n-joint articulated arm. We show that the combined underactuated system is differentially flat, however the flat outputs do not correspond directly to the motion of the end effector. We therefore develop a method which determines the family of flat output trajectories which will exactly produce any desired task trajectory, even in the case of dynamic maneuvers. We also give criteria on the manipulator geometry which will ensure certain important stability properties, informing hardware design. The entire approach is demonstrated in simulation for systems of varying geometry and number of joints. The simultaneous resolution of the kinematic and dynamic constraints allows these tasks to be performed dynamically without sacrificing accuracy.

<iframe width="420" height="315" src="https://www.youtube.com/embed/GOc6Begdb2s" frameborder="0" allowfullscreen></iframe><br/>
