---
title: "Collaborative Edge Computing for LLM Inference"
excerpt: "Soft-deadline-aware scheduling of large language model inference requests across collaborating edge servers using a Transformer-enhanced PPO agent. <br/><span class='tags'>LLM serving · MEC · PPO · Transformers</span>"
collection: portfolio
order: 2
---

**Venue:** IEEE GLOBECOM 2026 (SAC: Cloud/Edge Computing and Networking), Macau<br/>
**Links:** [arXiv preprint](https://arxiv.org/abs/2608.02031)

## Problem

LLM inference at the network edge is expensive and latency-sensitive. A single edge server is often not enough, and requests have *soft* deadlines: a late answer still has value, but less of it.

## Approach

- Formulated collaborative offloading of LLM inference across multiple edge servers with soft-deadline utility.
- Proposed a **PPO agent enhanced with a Transformer encoder** that attends over the current queue of requests and server states to decide where and when each request is served.

## Role

First author, together with Prof. Björn Landfeldt (Lund University).
