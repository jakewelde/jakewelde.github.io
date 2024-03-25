---
short_title: "Target Tracking"
title: "Autonomous Flight for Detection, Localization, and Tracking of Moving Targets With a Small Quadrotor"
excerpt: ""
collection: portfolio
thumbnail: "/images/tracking.png"
year: 2017
publications:
  - key: Thomas2017
---

2017 

*with Justin Thomas, Giuseppe Loianno, Kostas Daniilidis, and Vijay Kumar*

{% include figure image_path="/images/tracking.png" caption="The aerial vehicle detects the moving target using its downward camera. It reacts, keeping the target in the field of view while converging to match the target's motion." %}


In this work, we enable a small quadrotor to autonomously track a moving target and plan trajectories that allow the robot to converge on the target. Our approach respects the dynamic, sensor, and actuator constraints of the vehicle, in particular ensuring that the target does not leave the field of view of the camera, which is rigidly attached to the robot and therefore affected by the coupled dynamics of the system. One of the major contributions of this work is that all sensing and computation is done onboard the 250 g vehicle, with no outside assistance from motion capture systems or external processors.

<iframe width="420" height="315" src="https://www.youtube.com/embed/LDE1jyyQUWc" frameborder="0" allowfullscreen></iframe><br/>
