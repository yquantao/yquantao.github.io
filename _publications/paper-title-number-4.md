---
title: "Variable Impedance Skill Learning for Contact-Rich Manipulation"
collection: publications
permalink: /publications/yang2022variable
venue: "IEEE Robotics and Automation Letters"
date: 2022-07-10
#citation: '<b>Quantao Yang</b>, Johannes Andreas Stork, and Todor Stoyanov. <i>NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)</i>.'
---

[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812508)


## Abstract
Contact-rich manipulation tasks remain a hard
problem in robotics that requires interaction with unstructured
environments. Reinforcement Learning (RL) is one potential solution to such problems, as it has been successfully demonstrated on
complex continuous control tasks. Nevertheless, current state-ofthe-art methods require policy training in simulation to prevent
undesired behavior and later domain transfer even for simple
skills involving contact. In this paper, we address the problem
of learning contact-rich manipulation policies by extending an
existing skill-based RL framework with a variable impedance
action space. Our method leverages a small set of suboptimal
demonstration trajectories and learns from both position, but also
crucially impedance-space information. We evaluate our method
on a number of peg-in-hole task variants with a Franka Panda
arm and demonstrate that learning variable impedance actions
for RL in Cartesian space can be deployed directly on the real
robot, without resorting to learning in simulation.
