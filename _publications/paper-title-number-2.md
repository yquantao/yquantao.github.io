---
title: "Learning Impedance Actions for Safe Reinforcement Learning in Contact-Rich Tasks"
collection: publications
permalink: /publications/yang2021learning
venue: "NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)"
date: 2021-12-06
#citation: '<b>Quantao Yang</b>, Johannes Andreas Stork, and Todor Stoyanov. <i>NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)</i>.'
---

[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9568848)

## Abstract
Reinforcement Learning (RL) has the potential of solving complex continuous
control tasks, with direct applications to robotics. Nevertheless, current stateof-the-art methods are generally unsafe to learn directly on a physical robot as
exploration by trial-and-error can cause harm to the real world systems. In this
paper, we leverage a framework for learning latent action spaces for RL agents
from demonstrated trajectories. We extend this framework by connecting it to a
variable impedance Cartesian space controller, allowing us to learn contact-rich
tasks safely and efficiently. Our method learns from trajectories that incorporate
both positional, but also crucially impedance-space information. We evaluate our
method on a number of peg-in-hole task variants with a Franka Panda arm and
demonstrate that learning variable impedance actions for RL in Cartesian space
can be safely deployed on the real robot directly, without resorting to learning in
simulation and a subsequent policy transfer.
