---
title: "Capacity-dependent theory for kernel score estimation"
excerpt: "A derivative-weighted effective dimension that gives capacity-dependent rates for kernel score estimation, with a matching minimax lower bound and guarantees at every diffusion time."
collection: portfolio
period: "Jan 2026 – Aug 2026"
status: "Accepted at NeurIPS 2026 Workshop BeNTo (Oct 2026)"
---

**Role:** First author · **Jan 2026 – Aug 2026** · NeurIPS 2026 Workshop BeNTo

### The question

Diffusion models need an estimate of the score — the gradient of the
log-density — at every noise level. Existing rates for kernel score estimation
are capacity-independent and ignore that the target is a derivative. How fast
can the score actually be learned, and what governs the rate?

### What I did

* Introduced a **derivative-weighted effective dimension** for kernel score
  estimation.
* Proved capacity-dependent rates of order
  $\widetilde{O}_P\big(M^{-(r+1/2)/(2r+1+\alpha)}\big)$, beyond
  capacity-independent bounds.
* Computed the derivative penalty exactly ($2/A$) for diagonal and curl-free
  kernels on the torus, and proved a **matching minimax lower bound**.
* Showed that the guarantees hold **at every diffusion time**.

### Output

*Derivative-Weighted Capacity Bounds for Kernel Score Estimation*,
NeurIPS 2026 Workshop BeNTo.

**Tools:** RKHS theory, spectral analysis, empirical-process bounds; Python / JAX for numerical checks.
