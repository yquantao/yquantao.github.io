---
title: "Null Space Based Efficient Reinforcement Learning with Hierarchical Safety Constraints"
collection: publications
permalink: /publications/yang2021null
venue: "European Conference on Mobile Robots (ECMR 2021), Virtual meeting."
date: 2021-08-31
#citation: '<b>Quantao Yang</b>, Johannes Andreas Stork, and Todor Stoyanov. <i>European Conference on Mobile Robots</i>. <b>ECMR 2021</b>.'
---

[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9568848)

## Abstract
Reinforcement learning is inherently unsafe for
use in physical systems, as learning by trial-and-error can cause
harm to the environment or the robot itself. One way to avoid
unpredictable exploration is to add constraints in the action
space to restrict the robot behavior. In this paper, we propose
a null space based framework of integrating reinforcement
learning methods in constrained continuous action spaces. We
leverage a hierarchical control framework to decompose target
robotic skills into higher ranked tasks (e. g., joint limits and
obstacle avoidance) and lower ranked reinforcement learning
task. Safe exploration is guaranteed by only learning policies
in the null space of higher prioritized constraints. Meanwhile
multiple constraint phases for different operational spaces are
constructed to guide the robot exploration. Also, we add penalty
loss for violating higher ranked constraints to accelerate the
learning procedure. We have evaluated our method on different
redundant robotic tasks in simulation and show that our null
space based reinforcement learning method can explore and
learn safely and efficiently.
