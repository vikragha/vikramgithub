---
layout: page
permalink: /projects/
title: Selected Projects
tags: [projects]
modified: 9-10-2019
comments: false
---

Some of my projects in process are presented here.

### Reinforcement Learning
* **Multi-Agent Resource Optimization Platform**<br>
Collaborating: <b>Microsoft Research Asia</b><br>
MARO (Multi-Agent Resource Optimization) is an end-to-end platform for applied multi-agent reinforcement learning based on resource allocation optimization. The motivation for MARO was to provide as much flexibility for procedurally networked multi-agent scenarios and to support multi-agent distributed algorithm training.
<br/>
MARO offers various graph based multi-agent environments and popular deep RL algorithm implementations. The platform includes agents' information (state, action, reward) engineering, environment runner, user-defined business engine and distributed training modules. MARO natively supports PyTorch.

 <p align="center" ><img src="{{ site.url }}/images/MARO.jpg"></p>


* **Motivation Engineering in Graph-based Multi-Agent Reinforcement Learning**<br>
Collaborating: <b>University of California, Los Angeles</b><br>
In networked multi-agent reinforcement learning, we argue that individual reward engineering can motivate agents' cooperation.
<br />
Considering sequential resource allocation scenarios such as logistic network and routing, a variety of methods are proposed for motivation design in learning with graph feature processing. We introduce an attention mechanism to infer agents' individual action influence. To adapt scalability of large networked multi-agent system, we represent sub-graph layers and graph-layer attention for influence propagation.
<br />
Also, we now consider a method to calculate agents' contribution in cooperation task to improve cooperative performance. It is also a motivation engineering problem in MARL.
<br />
Our work papers will be published soon.

* **Cooperative Policy Representation in Meta Reinforcement Learning**<br>
Collaborating: <b>Carnegie Mellon University</b><br>
Methods for representing networked agents' interaction in multi-agent system.
<br />
Considering a new agent as a new node in a multi-agent system, We introduce an graph interaction representation for learning agent adaptation in a new environment.

* **Local Differential Privacy in Decentralized Multi-Agent Learning**<br>
Collaborating: <b>Carnegie Mellon University</b><br>
Inspired from federated learning, we now study local differential privacy in the cooperative framework of centralized training with decentralized execution. In the other words, different local privacy-preserving approaches are applied in multi-agent learning.

### Human Robot Interaction

* **ASIST: A Robust and Adaptive Agent that Supports High Performance Teams**<br>
Collaborating: <b>Carnegie Mellon University</b>, <b>DARPA</b><br>
The ASIST project involves human team behavior monitoring, prediction, and robot assistance. We now develop an end-to-end theory of mind model (a modularized neural network) to understand and predict human behaviors, for large decentralized teams with humans in specific roles.
<br />
Our model is used to develop a generalizable and scalable agent architecture (ASIST agent) which can assist human teamwork by providing needed information about environment and teammates' actions to help the human team be robust to teammates' and environmental perturbations.
