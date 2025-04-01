---
title: "A Comprehensive Framework for Human-Cable Physical Interaction Management in Cable-Driven Parallel Robots: Safety Handling and Collaborative Mitigation"
collection: publications
category: manuscripts
permalink: /publication/2025-09-31-Comprehensive-Framework
status: Under Review
excerpt: 'This paper presents a comprehensive framework for managing physical interactions between humans and cables in Cable-Driven Parallel Robots (CDPRs). We propose an optimal method for computing various workspace configurations while accounting for experimental uncertainties. Additionally, we introduce a physical interaction model designed to accurately estimate both the contact points and the exerted forces during human-cable interactions. Leveraging a workspace classification approach, we develop a robust compliance trajectory planning strategy that respects workspace boundaries, effectively navigating the robot towards feasible regions for safe cable release.'
date: 2025-09-31
venue: 'Under review'
---

## Abstract

In this work, we propose robust methods to estimate the external wrench acting on the Moving Platform (MP) without mounting sensors on the MP. We implement an elasto-plastic compliance controller to enable collaborative behavior during direct physical contact. The plasticity and elasticity of this controller are tuned via reinforcement learning, leveraging the estimated force and the robot’s current state.

### Inspiration

This work is inspired by the following papers:

1. **Human-Robot Collaboration**  
   Li, Guanrui; Liu, Xinyang; Loianno, Giuseppe.  
   *Human-Aware Physical Human–Robot Collaborative Transportation and Manipulation With Multiple Aerial Robots.*  
   IEEE Transactions on Robotics, vol. 41, pp. 762–781, 2025.  
   [doi:10.1109/TRO.2024.3502508](https://doi.org/10.1109/TRO.2024.3502508)

2. **Elasto-Plastic Compliance Controller**  
   Michael Panzirsch, Harsimran Singh, Xuwei Wu, et al.  
   *Virtual elasto-plastic robot compliance to active environments.*  
   Science Robotics, vol. 10, no. 99, 2025, eadq1703.  
   [doi:10.1126/scirobotics.adq1703](https://doi.org/10.1126/scirobotics.adq1703)

3. **Reinforcement Learning for Compliance Path Design**  
   Yunlong Song, Angel Romero, Matthias Müller, Vladlen Koltun, Davide Scaramuzza.  
   *Reaching the limit in autonomous racing: Optimal control versus reinforcement learning.*  
   Science Robotics, vol. 8, no. 82, 2023, eadg1462.  
   [doi:10.1126/scirobotics.adg1462](https://doi.org/10.1126/scirobotics.adg1462)

