---
title: "MPR-RL: Multi-Prior Regularized Reinforcement Learning for Knowledge Transfer"
collection: publications
permalink: /publications/yang2022mpr
venue: "IEEE Robotics and Automation Letters"
date: 2022-06-22
#citation: '<b>Quantao Yang</b>, Johannes Andreas Stork, and Todor Stoyanov. <i>NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)</i>.'
---

[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9803274)

## Abstract
In manufacturing, assembly tasks have been a challenge for learning algorithms due to variant dynamics of different environments. Reinforcement learning (RL) is a promising
framework to automatically learn these tasks, yet it is still not
easy to apply a learned policy or skill, that is the ability of
solving a task, to a similar environment even if the deployment
conditions are only slightly different. In this paper, we address the
challenge of transferring knowledge within a family of similar
tasks by leveraging multiple skill priors. We propose to learn
prior distribution over the specific skill required to accomplish
each task and compose the family of skill priors to guide learning
the policy for a new task by comparing the similarity between
the target task and the prior ones. Our method learns a latent
action space representing the skill embedding from demonstrated
trajectories for each prior task. We have evaluated our method
on a task in simulation and a set of peg-in-hole insertion
tasks and demonstrate better generalization to new tasks that
have never been encountered during training. Our Multi-Prior
Regularized RL (MPR-RL) method is deployed directly on a real
world Franka Panda arm, requiring only a set of demonstrated
trajectories from similar, but crucially not identical, problem
instances.
