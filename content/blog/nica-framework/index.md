---
title: "NICA: The Neuro-Inspired Computational Architecture for Behavioral Decisions"
summary: "A bridge between neural value integration and discrete choice models. Introducing NICA to unify vmPFC-driven value encoding with empirical wait-time parameters."
date: 2026-03-28
authors:
  - admin
tags:
  - Computational Neuroscience
  - Behavioral Economics
  - NICA
  - DDM
  - vmPFC
image:
  caption: 'The NICA Framework'
  focal_point: 'Smart'
  preview_only: false
---

How does the human brain bridge the gap between a **neural signal** in the prefrontal cortex and an **empirical choice** recorded in a survey? 

Introducing **NICA** (Neuro-Inspired Computational Architecture), a conceptual and computational framework I've developed to unify my PhD research findings into a single, cohesive model of decision-making.

## The Logic of NICA

At its core, NICA is a multi-layered architecture that simulates how humans evaluate trade-offs between **waiting time** and **clinical efficacy**. It consists of three primary modules:

1.  **Value Integration (vmPFC)**: The ventromedial Prefrontal Cortex (vmPFC) acts as the "value hub." Here, I represent the utility of a vaccine not as a fixed number, but as a dynamically integrated signal that factors in clinical results and the "cost of delay."
2.  **Evidence Accumulation (DDM)**: The choice is modeled as a **Drift Diffusion Model (DDM)**. The "drift rate" (the speed at which we move toward a decision) is directly modulated by the neural value signal from the vmPFC.
3.  **Parameter Injection (Empirical)**: This is where the NICA framework becomes powerful. It takes the real-world parameters from my dissertation:
    *   **$\kappa = 0.225$**: The scaling factor for wait-time sensitivity.
    *   **$\delta = 0.160$**: The hyperbolic discounting rate derived from 1,027 respondents in Wuhan.

## Validating NICA

When I injected these empirical values into the NICA simulation, the architecture produced a **Behavioral Decision Metric (BDM) of 1.29**. This value remarkably aligns with the observed choice patterns in the survey data, effectively "closing the loop" between neural architecture and behavioral outcomes.

Furthermore, NICA's "decoding" of the decision process yields a **Monthly Willingness to Accept (MWTA) of 44.8 RMB/month**. This provides a concrete economic value for the psychological burden of a one-month delay.

## Why This Matters for Behavioral AI

NICA isn't just a model of human behavior; it's a blueprint for **Behavioral AI Architectures**. 

As we move toward agents that can truly model human preferences—like the "Digital Familiars" we're building in OpenClaw—architectures like NICA will be essential. They allow us to create AI that doesn't just "predict" choice, but "understands" the underlying neural and economic friction that drives it.

---
*Stay tuned as I further refine the NICA framework and integrate it into my future research at UC Berkeley and beyond.*
