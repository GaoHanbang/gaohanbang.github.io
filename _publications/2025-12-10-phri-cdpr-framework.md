---
title: "A Comprehensive Framework for Safety and Collaborative Management of Physical Human–Robot Interaction in Cable-Driven Parallel Robots"
collection: publications
category: manuscripts
permalink: /publication/2025-12-10-phri-cdpr-framework
status: Under Review
excerpt: "This manuscript proposes a unified, feasibility-aware framework for safe and effective physical human–robot interaction (pHRI) in cable-driven parallel robots (CDPRs). The approach jointly manages human–cable and human–moving-platform (MP) contacts by combining collided-cable stiffness reduction with MP-level elasto-plastic trajectory compliance, while a feasibility-aware safety manager monitors wrench-feasible conditions and prevents workspace failure under sensing and estimation uncertainties. Experiments on a large-scale CDPR demonstrate safe contact handling, continued task execution after collisions, and favourable collaborative behaviour, with an analysis of the associated energy implications."
date: 2025-12-10
venue: "IEEE Transactions on Robotics (Under review)"
--- 

## Abstract (short overview)

Cable-Driven Parallel Robots (CDPRs) are increasingly deployed in human-shared environments, yet safe and effective physical Human–Robot Interaction (pHRI) remains challenging due to human–cable impacts, human–platform contacts, large workspaces, and practical uncertainty in pose and wrench estimation. This paper proposes a comprehensive framework that jointly addresses human–cable and human–MP interactions within a single safety-first formulation. The method combines (i) collided-cable stiffness reduction together with compliant trajectory adaptation, (ii) an elasto-plastic compliance model designed for transparency and stability without direct force sensing at the MP, and (iii) a feasibility-aware safety manager that enforces wrench-feasible conditions and safe reconfiguration. Experiments with repetitive collaborative tasks validate safe contact handling, continuous task execution after collisions, and favourable collaborative behaviour, while characterising energy implications.

![Scheme of the proposed framework](/images/scheme_tro.png "Scheme of the proposed framework")

## Key contributions (high level)

- **Unified pHRI management for CDPRs:** A single framework handling both human–cable and human–MP physical contacts.
- **Cable-stiffness reduction + trajectory compliance:** Controlled tension release for the contacted cable paired with MP compliant motion.
- **Feasibility-aware safety management:** Online monitoring of wrench-feasible conditions to prevent workspace failure under interaction.
- **Experimental validation:** Repetitive collaborative task studies showing safety, continuity, and energy-characterisation results.


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

