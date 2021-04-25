---
title: "Policy, policy, policy"
date: 2021-04-25T13:32:19+01:00
draft: true
---

Can we govern by machine
<!--more-->

### Reducing policy to a learned agent

Reinforcement learning works pretty well in closed systems.

Shall we simply train an RL agent to determine which emissions to reduce to improve air quality?

We can build a model of air quality, particularly ozone and particulate matter (PM), and simply train an RL agent to take the appropriate measures to reduce ozone.

This would involve weighing up the benefits to quality of life from reducing air pollution against the possible costs of economic damage caused by reducing emissions, and the effect of that on quality of life. They are both tricky to model.

But an RL agent may be able to determine an optimal policy based on the information of the model. I think this could be a fascinating approach.

The performance of the RL agent, if put into production, would depend a great deal on the accuracy of the model in representing the world.
