---
title: "A Safety Framework for Collaborative Human–Robot Interaction in Cable-Driven Parallel Robots"
collection: publications
category: manuscripts
permalink: /publication/2026-05-29-safety-framework-phri-cdpr
status: Under Review
excerpt: "This manuscript submitted to IEEE Transactions on Robotics proposes a feasibility-aware supervisory framework that unifies safety-critical and collaborative physical human–robot interaction (pHRI) in Cable-Driven Parallel Robots (CDPRs) using only onboard cable-tension sensing. By coordinating compliant Moving-Platform (MP) motion with contacted-cable tension regulation, the framework promotes a cable from a hazard to a controlled interaction channel. The central novelty is an interaction strategy supervisor that decides whether releasing a contacted cable is robustly feasible at the current MP pose before any tension is reduced, otherwise routing the response through MP-level compliance alone. Supporting components include an elasto-plastic compliance law for workflow continuity and a bounded contacted-cable tension regulation law. Experiments on the CRAFT platform validate unified mode transitions, force consistency against a handle-mounted F/T sensor, and usability for 23 novice participants."
date: 2026-05-29
venue: "IEEE Transactions on Robotics (Under review)"
paperurl: "http://gaohanbang.github.io/files/26-0930_01_MS.pdf"
---

## Abstract (short overview)

As Cable-Driven Parallel Robots (CDPRs) move into human-shared workspaces, human factors must be treated as a primary design objective to enable safe and usable collaboration. In practice, operators may contact a cable or the Moving-Platform (MP) during operation; although cables are traditionally considered hazards, we instead promote them to a controlled interaction channel capable of carrying both disturbances and cooperative intent. We introduce a feasibility-aware supervisory framework that unifies safety-critical and collaborative pHRI in CDPRs using only onboard cable-tension sensing, by coordinating compliant MP motion with contacted-cable tension regulation. The central novelty is an interaction strategy supervisor that decides whether releasing a contacted cable is robustly feasible at the current MP pose before any tension is reduced, and otherwise routes the response through MP-level compliance alone. Supporting this decision leads to two new control components: an elasto-plastic compliance law that provides workflow continuity between safety reaction and intentional guidance, and a cable-tension regulation law that bounds the contacted cable below a prescribed limit while preserving wrench balance. Experiments on a CDPR platform, named CRAFT, validate three claims: an interaction-flow scenario demonstrates unified transitions across interaction modes; repeated-task trials quantify transparency, force consistency (cross-checked against a handle-mounted F/T sensor), and non-amplifying MP-level energetics; and user trials with novices assess usability and collaborative accessibility.

![Block diagram of the proposed framework](/images/fig04_framework_block_diagram.png "Block diagram of the proposed framework for pHRI management in a CDPR")

## Key contributions (high level)

- **Interaction strategy supervisor:** A decision layer that, given contact information, selects among three strategies (compliant MP response only; release and bound the contacted cable; release plus workspace-boundary repulsion). The decision is driven by a robust release-feasibility test that checks, before any tension is reduced, whether the contacted cable can be kept below a prescribed bound at the current pose under bounded tension and length-tracking uncertainties.
- **Elasto-plastic compliance for workflow continuity:** An MP-level compliance law that continuously updates a plastic equilibrium with an explicit restoration term, linking reflexive safety reaction, sustained cooperative guidance, and return to nominal motion using only cable-tension–derived wrench estimates.
- **Bounded contacted-cable tension regulation:** Rather than driving the contacted cable to slackness, the tension is regulated below a prescribed admissible bound via a scheduled QP upper bound and a reference override on the corresponding servomotor, preserving wrench feasibility and making the cable usable as a handle for collaboration.
- **Systems-level validation across three scales:** An interaction-flow experiment validates unified transition handling across interaction modes; repeated-task trials quantify compliance transparency, force consistency (including a dynamic comparison of the model-based wrench estimate with a handle-mounted F/T sensor), and non-amplifying power exchange at the MP; user trials with $N=23$ novices assess usability and collaborative accessibility.


