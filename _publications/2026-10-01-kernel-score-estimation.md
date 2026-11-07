---
title: "Derivative-Weighted Capacity Bounds for Kernel Score Estimation"
collection: publications
category: conferences
selected: true
permalink: /publication/2026-10-01-kernel-score-estimation
redirect_from:
  - /publication/2026-09-01-kernel-score-estimation
excerpt: 'Capacity-dependent learning rates for kernel score estimation via a derivative-weighted effective dimension, with a matching minimax lower bound and guarantees that hold at every diffusion time.'
date: 2026-10-01
venue: 'NeurIPS 2026 Workshop BeNTo'
citation: 'Thanh Nguyen, et al. (2026). &quot;Derivative-Weighted Capacity Bounds for Kernel Score Estimation.&quot; <i>NeurIPS 2026 Workshop BeNTo</i>.'
---

<!-- TODO: add paperurl (OpenReview / arXiv) and bibtexurl when available. -->

**Summary.** Score-based diffusion models learn the gradient of the log-density
at every noise level. This paper studies how fast that score can be learned
with kernel methods, and shows that the right notion of model capacity must
account for the fact that a score is a *derivative*.

**What the paper does**

* Introduces a **derivative-weighted effective dimension** for kernel score
  estimation.
* Obtains capacity-dependent rates of order
  $\widetilde{O}_P\big(M^{-(r+1/2)/(2r+1+\alpha)}\big)$, improving on
  capacity-independent bounds.
* Computes the derivative penalty exactly ($2/A$) for diagonal and curl-free
  kernels on the torus, and proves a **matching minimax lower bound**.
* Shows that the guarantees hold **at every diffusion time**, not only at a
  fixed noise level.

**Why it matters.** Rates for score estimation are the statistical backbone of
diffusion-model theory. Making them capacity-dependent explains when a smoother
kernel actually helps, and by how much.
