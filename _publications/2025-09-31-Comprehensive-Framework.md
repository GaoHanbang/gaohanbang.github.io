---
title: "A Comprehensive Framework for Human-Cable Physical Interaction Management in Cable-Driven Parallel Robots: Safety Handling and Collaborative Mitigation"
collection: publications
category: manuscripts
permalink: /publication/2025-09-31-Comprehensive-Framework
status: Under Review
youtube: "https://www.youtube.com/embed/nGuaomoOP80"
excerpt: 'This paper presents a comprehensive framework for managing physical interactions between an opeator and a cable in Cable-Driven Parallel Robots (CDPRs). We propose an optimal method for computing various workspace configurations while accounting for experimental uncertainties. Additionally, we introduce a physical interaction model designed to accurately estimate both the contact points and the exerted forces during human-cable interactions. Leveraging a workspace classification approach, we develop a robust compliance trajectory planning strategy that respects workspace boundaries, effectively navigating the robot towards feasible regions for safe cable release.'
date: 2025-09-31
venue: 'Under review'
---

## Abstract

This paper presents a comprehensive framework for managing physical interactions between an operator and a cable in Cable-Driven Parallel Robots (CDPRs).  
![Prototype of the CRAFT system and human-cable physical interaction](/images/scheme_CRAFT.png "Prototype of the CRAFT system and human-cable physical interaction")

We propose an optimal method for computing various workspace configurations—including the collision-free workspace, restrained feasible workspace, and static feasible workspace—while accounting for experimental uncertainties such as tension measurement errors and joint encoder inaccuracies.

Furthermore, we introduce a physical interaction model capable of accurately estimating both the contact point and the exerted forces during human-cable interactions. This model achieves less than 15% error in position estimation and under 10% in force estimation, all without requiring direct measurements.  
![Physical human-cable contact model](/images/Identification_scheme.png "Physical human-cable contact model")

Building upon a workspace classification strategy, we develop a robust compliant trajectory planning method that adheres to workspace boundaries, enabling the robot to safely transition toward feasible regions for controlled cable release.

