---
short_title: "Geometric Tracking Control"
title: "Tracking Control on Homogeneous Riemannian Manifolds"
excerpt: ""
collection: portfolio
thumbnail: "/images/sphere_tracking.gif"
year: 2024
publications:
  - key: Welde2024
---

2024

*with Vijay Kumar*

{% include figure image_path="/images/sphere_tracking.gif" caption="The proposed method, applied to tracking control for a fully-actuated mechanical system on $$\mathbb{S}^2$$. Here, we visualize rollouts of the tracking controller from 100 randomly sampled initial states in $$T\mathbb{S}^2$$. Because the controller achieves almost global asymptotic tracking, the probability that a randomly sampled initial condition fails to converge to the reference trajectory is *exactly zero*." %}


In this work, we address the design of tracking
controllers that drive a mechanical system’s state asymptotically
towards a reference trajectory. Motivated by aerospace and
robotics applications, we consider fully-actuated systems evolving on the broad class of homogeneous spaces (encompassing all
vector spaces, Lie groups, and spheres of any dimension). In this
setting, the transitive action of a Lie group on the configuration
manifold enables an intrinsic description of the tracking error
as an element of the state space, even in the absence of a group
structure on the configuration manifold itself (e.g., for $$\mathbb{S}^2$$). Such
an error state facilitates the design of a generalized control
policy depending smoothly on state and time that drives this
geometric tracking error to a designated origin from almost
every initial condition, thereby guaranteeing almost global
convergence to the reference trajectory. Moreover, the proposed
controller simplifies naturally when specialized to a Lie group
or the $$n$$-sphere. In summary, we propose a unified, intrinsic
controller guaranteeing almost global asymptotic trajectory
tracking for fully-actuated mechanical systems evolving on
a broader class of manifolds. We apply the method to an
axisymmetric satellite and an omnidirectional aerial robot.