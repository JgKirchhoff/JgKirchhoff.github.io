---
permalink: /inverse-problems/
title: "Inverse Problems & Digital Twins"
author_profile: true
---

## From Images to Material Fields

In many engineering systems, the quantities we care about most — material parameters, defects, internal stresses — are not directly measurable. Instead, we observe system responses (displacements, temperature fields, strain maps) and solve an **inverse problem** to infer the underlying parameters.

My research focuses on *high-dimensional inverse problems*, where the unknown is not a single number, but a spatially varying field that parametrizes a partial differential equation.

This setting is essential for modern manufacturing:  
if we want to detect non-conformities, voids, or heterogeneous bonding regions, the parameter space must be rich enough to represent them.

These problems are inherently ill-posed. To address this, we develop function-space formulations with principled regularization and scalable Newton–Krylov solvers that remain consistent in the infinite-dimensional limit.

---

## ∞–IDIC: Infinite-Dimensional Integrated Digital Image Correlation

We developed **∞–IDIC**, an infinite-dimensionally consistent formulation of Integrated Digital Image Correlation.

Traditional DIC methods estimate displacement fields and then post-process them to infer material properties. In contrast, ∞–IDIC directly inverts for spatially varying material parameters by coupling:

- Image data  
- Governing PDEs of elasticity  
- Function-space regularization  

The result is a scalable algorithm capable of recovering **heterogeneous modulus fields** from static loading experiments.

This enables:

- Non-destructive identification of material heterogeneity  
- Discovery of voids and non-conformities  
- Inference of modulus-induced stress fields  
- A pathway toward mechanics-aware digital twins  

For more details, see our preprint and technology disclosure:
- [Infinite-Dimensional IDIC Preprint](https://arxiv.org/abs/2408.10217)  
- [Technology Page](https://utotc.technologypublisher.com/technology/54454)

---

## Example: Recovering a Spatial Modulus Field

Below, ∞–IDIC reconstructs a spatially varying elastic modulus profile (Bevo-shaped) from four different static loading configurations.

### Compression
<img src="/images/longhorn_compression.gif" width="800" />

### Tension
<img src="/images/longhorn_tension.gif" width="800" />

### Bending (Down)
<img src="/images/longhorn_bending1.gif" width="800" />

### Bending (Up)
<img src="/images/longhorn_bending2.gif" width="800" />

Across loading conditions, the method consistently reconstructs the underlying heterogeneous field — demonstrating robustness and physics consistency.

---

## Toward Manufacturing Digital Twins

The long-term goal is to integrate these inverse methods into real manufacturing workflows.

By combining:
- High-resolution experimental measurements (SEM-DIC, micro-scale testing)  
- Bayesian uncertainty quantification  
- Neural-operator surrogates for accelerated PDE solves  

we move toward real-time, mechanics-aware digital twins for thermoplastic composite manufacturing.

Inverse problems are not just a computational tool in this framework — they are the bridge between experiments and predictive manufacturing systems.
