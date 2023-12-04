---
short_title: "An Invisible Tripod"
title: "SharpShooter: an Invisible Tripod for Long-Exposure Photography"
excerpt: "How can we stabilize a handheld camera during a long exposure automatically and in an ergonomic manner?"
collection: portfolio
thumbnail: "/images/sharpshooter.jpg"
year: 2019
gallery:
  - url: sharpshooter/strap.jpg
    image_path: sharpshooter/strap.jpg
  - url: sharpshooter/use.jpg
    image_path: sharpshooter/use.jpg
  - url: sharpshooter/core.jpg
    image_path: sharpshooter/core.jpg
  - url: sharpshooter/exploded.jpg
    image_path: sharpshooter/exploded.jpg
  - url: sharpshooter/back.jpg
    image_path: sharpshooter/back.jpg
  - url: sharpshooter/device.jpg
    image_path: sharpshooter/device.jpg
gallery2:
  - url: sharpshooter/library.jpg
    image_path: sharpshooter/library.jpg
    title: The Fisher Fine Arts Library (the Furness library).
  - url: sharpshooter/stadium.jpg
    image_path: sharpshooter/stadium.jpg
    title: Franklin Field.
  - url: sharpshooter/singh.jpg
    image_path: sharpshooter/singh.jpg
    title: The Singh Center for Nanotechnology.
---
Mechanical Engineering Senior Design 2019

*with Matt Oslin, Karina Gunadi, Paul Flores, Miltos Kitsios, and Bennet Caraher*

![image-center](/images/sharpshooter.jpg){: .align-center}

For our senior design capstone project, we created a camera stabilization device for long exposure photography unlike any other available on the market.

Photographers require long shutter speeds to allow them to capture the desired shot in challenging scenes, such as in low light conditions or when high depth of field is critical. The problem is that tiny movements of the photographer’s hands during the exposure will blur to photo so much as to be unusable for shutter speeds over about 1/30 sec. Existing solutions for stabilization such as tripods, in body stabilization, and optical stabilization all fall short either due to their lack of portability or their severe exposure length limits.

{% include gallery %}

Enter SharpShooter, a self-contained stabilization device that automatically activates when the user takes a photo. SharpShooter is inspired by reaction wheel attitude control systems used in satellites. By applying torques to internal flywheels in response to extremely small motion sensed by SharpShooter’s inertial measurement unit, the device actively corrects for the disturbances introduced by the user, just like noise-canceling headphones do for audio playback.

{% include figure image_path="/images/sharpshooter/performance.png" caption="SharpShooter outperformed all other handheld stabilization devices available on the market." %}

{% include figure image_path="/images/sharpshooter/comparison.gif" caption="The random disturbances caused by small motions of the photographer's hands during an exposure are drastically attenuated by SharpShooter." %}

{% include gallery id="gallery2" caption="Testing SharpShooter at night by photographing buildings around campus (click to see detail)." %}

Many significant engineering challenges were tackled to make this idea reality. An extremely high level of responsiveness and performance was necessary to achieve exposures up to 2 seconds long. We developed precision reaction wheels through an iterative balancing and motor modeling process, including an optimization-based torque mapping methodology aimed to produce a model that is accurate in all regions of motor state space while efficient enough to compute at 600Hz on a microcontroller. Additionally, highly accurate gyroscope bias estimation was necessary to be able to accurately measure orientation deviations as small as 1/100 °. All of these subsystems then had to be tightly integrated into a package that was small and ergonomic enough for comfortable, on-the-go use by a photographer.

{% include figure image_path="/images/sharpshooter/team.jpg" caption="The best senior design teammates I could have asked for!" %} 

At Mechanical Engineering Senior Design Day, we won the award for Best Presentation and went on to place second in the School of Engineering-wide Senior Design Competition.

<iframe width="420" height="315" src="https://www.youtube.com/embed/0LzrWOefOeU" frameborder="0" allowfullscreen></iframe>