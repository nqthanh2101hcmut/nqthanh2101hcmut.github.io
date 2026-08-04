---
title: "Density-estimation-based objective design for generative models"
excerpt: "M.Res. thesis and ongoing research: a single density-estimation formulation that connects KL minimization with score-matching and flow-matching objectives, tested on convergence, stability and sample quality."
collection: portfolio
---

**Role:** Graduate Research Assistant, Department of Applied Mathematics, HCMUT
(VNU-HCM) · **Advisor:** Dr. Le Xuan Dai · **Mar 2025 – present**

This is the core of my M.Res. thesis, *Optimizing Score Flow Matching for
Generative Models Based on Density Estimation*.

### The question

Diffusion models, normalizing flows and variational autoencoders are usually
presented with separate training recipes. Each recipe is really a choice about
*what density-related quantity the loss estimates*. If that choice is made
explicit, the recipes stop being separate.

### What I did

* Derived a density-estimation formulation in which KL minimization,
  score matching and flow matching appear as specializations of one objective
  under different modelling assumptions.
* Investigated the theoretical and empirical properties of these objectives:
  what each estimates, how the estimator behaves, and where the approximations
  bite.
* Designed a comparative experimental protocol measuring convergence speed,
  training stability and sample quality across the formulations, so that
  differences are attributable to the objective rather than to tuning.
* Communicated the results through research reports and visual analyses.

### Output

Published as *Optimization of the Objective Function for Generative Models Based
on Distribution Density Estimation* (HCMUE Journal of Science, 2025), and
extended in the optimal-transport work below.

**Tools:** Python, PyTorch, NumPy, SciPy, Matplotlib.
