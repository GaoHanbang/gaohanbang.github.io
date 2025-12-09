---
title: "Input-to-State Robustness Control for Human–Cable Interaction in Cable-Driven Parallel Robots"
collection: publications
category: conferences
permalink: /publication/2026-ecc-iss-robustness-human-cable
status: Under Review
excerpt: "This paper develops a collision-aware control strategy for cable-driven parallel robots (CDPRs) during human–cable interaction. We propose a rapidly exponentially input-to-state stable Control Lyapunov Function (RES–ISS–CLF) controller and augment it with a QP-based tension distribution layer that enforces unilateral cable constraints while applying a smooth, time-varying upper-bound reduction on the contacted cable. The method is evaluated in a cable-wrapping simulator with an arm-like obstacle and shows stable tracking and improved post-contact behaviour compared with PID and CLF–QP baselines."
date: 2026-01-01
venue: "European Control Conference (ECC 2026, Under review)"
paperurl: "http://gaohanbang.github.io/files/ECC26.pdf"
citation: "R. Keskin, H. Gao, C. Chevallereau, and S. Caro. “Input-to-State Robustness Control for Human–Cable Interaction in Cable-Driven Parallel Robots.” Submitted to the European Control Conference (ECC), 2026."
---

## Overview

Cable-Driven Parallel Robots (CDPRs) provide large workspaces and high payload-to-mass ratios, but their cables are unilateral actuators: they can pull but cannot push, and they are prone to contact and wrapping in human-shared workspaces. During human–cable interaction, contact-induced disturbances can trigger abrupt tension variations and excite oscillations, making it difficult to simultaneously guarantee closed-loop stability, preserve tracking performance, and satisfy hard tension constraints.

This paper proposes a collision-aware control and tension-management approach that explicitly targets this regime. We design a rapidly exponentially input-to-state stable control Lyapunov function (RES–ISS–CLF) controller to provide robustness guarantees under external wrenches (including gravity and human contact). To enforce unilateral cable constraints during contact and recovery, we augment the controller with a quadratic programming (QP) tension distribution layer that applies a smooth, time-varying reduction of the upper bound on the contacted cable, while preserving feasibility of the overall wrench/tension allocation.

## Key contributions

1. **RES–ISS–CLF control design for CDPR pHRI.**  
   We formulate a rapidly exponentially input-to-state stabilising CLF-based controller tailored to CDPR tracking under bounded external disturbances, providing a principled stability guarantee during human–cable interaction.

2. **Collision-aware, constraint-enforcing tension management.**  
   We introduce a QP-based tension distribution strategy that enforces unilateral cable constraints and executes a smooth, detection-triggered reduction of the contacted-cable tension upper bound. This mitigates contact loads while improving transient behaviour during collision and recovery.

3. **Reproducible evaluation in a cable-wrapping simulator.**  
   We evaluate the method in a wrapping scenario where a fixed cylinder emulates an arm-like obstacle, enabling controlled study of contact dynamics, tension reallocation, and post-contact recovery.

4. **Comparative analysis against standard baselines.**  
   Performance is benchmarked against PID and CLF–QP controllers under matched tasks, reporting tracking quality and post-contact oscillation behaviour to highlight the benefit of combining ISS guarantees with hard constraint enforcement.

## Methods (high level)

The control architecture couples (i) an RES–ISS–CLF tracking controller with (ii) a QP tension allocator. Under contact, the allocator modifies feasible tension distributions by tightening the upper bound of the contacted cable with a time-varying schedule, thereby reducing effective cable stiffness and limiting peak contact loads. Throughout collision and recovery, the QP layer maintains unilateral constraints and feasibility, while the CLF design drives the system back towards the desired trajectory with input-to-state robustness.

## Results (summary)

Simulation studies in the cylinder-wrapping scenario show that the proposed RES–ISS–CLF–QP strategy maintains stable tracking under contact disturbances and exhibits improved post-contact behaviour relative to PID and CLF–QP baselines. In particular, the approach reduces oscillatory transients during collision and recovery while respecting unilateral cable constraints through the QP enforcement mechanism.
