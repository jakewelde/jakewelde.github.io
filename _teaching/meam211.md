---
title: "MEAM 211: Engineering Mechanics, Dynamics"
short_title: "Engineering Mechanics"
collection: teaching
# type: "Undergraduate course"
role: Head TA for Prof. Michael Posa
permalink: /teaching/meam211
venue: "University of Pennsylvania"
thumbnail: "/images/meam211/poinsot_sim.gif"
semester: "Spring 2021"
# location: "City, Country"
system_gallery:
  - url: meam211/coupled_oscillators.svg
    image_path: meam211/coupled_oscillators.svg
  - url: meam211/iss_handle.svg
    image_path: meam211/iss_handle.svg
algorithm_gallery:
  - url: meam211/kinematic_chain.svg
    image_path: meam211/kinematic_chain.svg
  - url: meam211/reaction.svg
    image_path: meam211/reaction.svg
iss_gallery:
  - url: meam211/t_handle_iss.gif
    image_path: meam211/t_handle_iss.gif
  - url: meam211/iss_sim.gif
    image_path: meam211/iss_sim.gif
poinsot_gallery:
  - url: meam211/poinsot_ellipsoid.gif
    image_path: meam211/poinsot_ellipsoid.gif
  - url: meam211/poinsot_sim.gif
    image_path: meam211/poinsot_sim.gif
sim_gallery:
  - url: meam211/double_cartpole.gif
    image_path: meam211/double_cartpole.gif
#   - url: meam211/spring_series.gif
#     image_path: meam211/spring_series.gif
  - url: meam211/spring_pendulum.gif
    image_path: meam211/spring_pendulum.gif
---

MEAM 211 is an undergraduate-level dynamics course taken by all mechanical engineering sophomores, covering fundamental techniques for modeling the dynamics of mechanical systems. While much of the course is focused on symbolic analysis, a computational component has become more of a focus in recent years.

As a Head TA for one semester, my role in the teaching team included developing computational assignments in MATLAB, designing and leading interactive problem solving recitations, and working directly with students in office hours on challenging homework problems and essential course concepts. I appreciated the guidance of Prof. Michael Posa and the collaboration of my co-Head TA Jessica Weakly, along with the masters student TA's.

{% include gallery id="iss_gallery" 
 caption="Demonstration of the Tennis Racket Theorem (instability of the intermediate axis of rotation of a rigid body) using the course simulator, compared to a [viral video](https://www.youtube.com/watch?v=1n-HMSCDYtM) from the International Space Station." 
 %}

Course Overview
==========================

MEAM 211 is a core requirement for undergraduate mechanical engineers, with several expected learning outcomes that are essential in mechanical engineering practice and analysis:

## 1. First-Principles Modeling of Mechanical Systems

By studying the Newton-Euler dynamics of a rigid body in 3D, and learning to compose those models via interconnecting elements like joints and springs, students learn a rigorous framework to derive the equations of motion of arbitrary mechanical systems.

{% include gallery id="system_gallery" layout="half"
 caption="Students study the dynamics of systems of rigid bodies coupled by elements like joints and springs." 
 %}


## 2. Building General Computational Tools for Dynamics

Because the equations of motion of coupled systems of rigid bodies quickly become intractible to derive or manipulate by hand, students learn to implement the underlying mathematical models in software. Via weekly step-by-step assignments, students gradually complete the features necessary to model and simulate arbitrary rigid body systems by exploiting a kinematic tree structure and recursion.

{% include gallery id="algorithm_gallery" layout="half"
 caption="To reinforce and exploit their new theoretical skills, students implement generalized algorithms in MATLAB to apply their dynamical modeling techniques automatically to generic rigid body systems." 
 %}

## 3. Using Conserved Quantities for System Analysis

Mechanical systems enjoy symmetries that lead to conserved quantities as described by [Noether's Theorem](https://en.wikipedia.org/wiki/Noether%27s_theorem). These conservation laws can simplify analysis, and can also be used as a "sanity check" to quickly point out implementation errors in a numerical simulation.

{% include gallery id="poinsot_gallery" 
 caption="Visualization of [Poinsot's Ellipsoids](https://en.wikipedia.org/wiki/Poinsot%27s_ellipsoid), showing how the angular velocity of a rigid body evolves over time along the intersection of two ellipsoids, respectively describing the conversation of energy and momentum." 
 %}

My Teaching Role
================

Alternating weeks with my co-Head TA, I was responsible for designing and leading interactive problem-solving recitations to complement the lecture material, comprising a mixture of individual and group work on analysis and computation problems and sometimes supplemented by coding exercises in MATLAB. I also enjoyed working closely with students in office hours to clear any remaining doubts.

In addition to working directly with students, I took on a significant role in the development of the computational assignments led by Prof. Michael Posa. I designed a portion of the simulator architecture, developed the testing infrastructure students could use to verify their solutions, and designed engaging demonstrations of the simulator to motivate students in their work.

{% include gallery id="sim_gallery"
 caption="By the end of the course, the students have implemented a rigid body simulator capable of automatically deriving and simulating the dynamics of arbitrary systems." 
 %}