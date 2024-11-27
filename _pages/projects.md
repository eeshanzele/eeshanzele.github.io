---
layout: archive
title: # "Projects"
permalink: /projects/
author_profile: false
redirect_from:
  - /projects/
---

{% include base_path %}

Reliable Autonomy Lab
======
I am working on computing *indistinguishable sets* in hybrid control systems to find key blindspots of these systems. I developed a computation technique parallelizing SMT solvers to compute these sets in high dimensional systems. Inspired by recent developments in latent-space learning, I also designed and verified neural networks to predict indistinguishable sets, for any hybrid control system fast and with formal guarantees of correctness.

<figure style="text-align: center; flex-direction: column; align-items: center; text-align: center;">
  <div style="display: flex; justify-content: center; align-items: center; gap: 0;">
  <img src="/images/rotate.gif" alt="Rotate" style="width: 300px; height: auto;">
  <img src="/images/shiftRotate.gif" alt="Shift Rotate" style="width: 300px; height: auto;">
</div>
  <figcaption style="margin-top: 1px; font-size: 14px; color: #555;">Example of iterative process computing indistinguishable set for 2D Dubin's Car System. Arrows represent agents in 2D space and heading angle. Black markers are landmarks. Agents with same colors are percieved as identical observation.</figcaption>
</figure> 

Intel
======
I worked as an intern with the Design Automation FE team at Intel, creating tools to streamline CPU model evaluation. I optimized a graph-based algorithm, saving an hour of computation time per day, and designed dashboards that are now widely used by the Design Automation team.


Illinois Theorem Provers Group
======
I worked with PhD student Hannah Leung, to formally verify Path ORAM, a RAM security primitive preventing attacks via memory access patterns. I helped develop algorithms to support RAM functionality, and provied their correctness using Coq. Co-authored conference paper proving functional correctness and security properties of Path ORAM (to be published soon).

Drifting MPC Controller
======
I helped implemented a pure persuit controllers optimized using a genetic algorithm, and a model predictive controller for the CARLA car racing simulator, ensuring robustness under various weather and track conditions Controllers developed beat benchmarks of racing times by 40 seconds (130%), while meeting safety requirements.
<div style="display: flex; justify-content: center; align-items: center; gap: 0;">
  <img src="/images/left.gif" alt="Rotate" style="width: 300px; height: auto;">
  <img src="/images/right.gif" alt="Shift Rotate" style="width: 300px; height: auto;">
</div>


Automated Proofs of Partition Congruences
======
As a part of the [Illinois Mathematics Lab](https://iml.math.illinois.edu/), worked with [Professor Scott Ahlgren](https://scottahlgren.web.illinois.edu/) and a group of undergraduate students automating proofs of partition congruences. Learnt modular forms, complex function theory and number theory to automate proofs of partition congruences, to reprove and improve 20+ published theorems of partition congruences using our methodology. [Paper](http://tinyurl.com/autoproofs) and [poster talk](http://tinyurl.com/posterautoproofs) on this work.

<figure style="text-align: center; flex-direction: column; align-items: center; text-align: center;">
  <div style="display: flex; justify-content: center; align-items: center; gap: 0;">
  <img src="/images/igl.jpeg" alt="IGLPic" style="width: 500px; height: auto;">
</div>
  <figcaption style="margin-top: 1px; font-size: 14px; color: #555;">IML Poster Talk with Prof. Ahlgren (center) and Tyler Cushing (right).</figcaption>
</figure> 