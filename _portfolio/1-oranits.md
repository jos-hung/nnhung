---
title: "Oranits: Mission Assignment and Task Offloading in Open RAN-based ITS"
excerpt: "Joint mission assignment and computation offloading for connected autonomous vehicles in Open RAN + MEC, solved with metaheuristics and deep reinforcement learning. <br/><span class='tags'>Open RAN · MEC · Metaheuristics · DRL · ITS</span>"
collection: portfolio
order: 1
---

**Venue:** IEEE Transactions on Intelligent Transportation Systems, 2026 · IEEE GLOBECOM 2025<br/>
**Links:** [Paper (DOI)](https://doi.org/10.1109/TITS.2026.3705751) · [arXiv](https://arxiv.org/abs/2507.19712) · [GLOBECOM 2025 slides](https://jos-hung.github.io/nnhung/files/Globecom2025.pdf)

## Problem

In intelligent transportation systems, autonomous vehicles must be assigned missions while offloading their computation-heavy tasks to edge servers. Mission assignment and task offloading are tightly coupled: where a vehicle drives determines which edge resources it can reach, and how fast its tasks are processed determines whether missions finish on time.

## Approach

- Modeled the system as an Open RAN-enabled ITS with mobile edge computing, capturing vehicle mobility, mission dependencies and edge resource constraints.
- Designed a **metaheuristic** solver for the joint mission assignment and offloading problem (GLOBECOM 2025).
- Extended it with a **deep reinforcement learning** controller for autonomous, adaptive decision-making in dynamic traffic conditions (IEEE T-ITS 2026).

## Role

First author: problem formulation, algorithm design, simulation and writing.
