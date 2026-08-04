---
title: "Ranking Objects Based on Multiplicative Consistency of Comparison Matrices: Logarithmic Minimax (Chebyshev) Model and Applications"
collection: publications
category: underreview
permalink: /publication/2026-07-01-ranking-multiplicative-consistency
excerpt: 'A logarithmic Chebyshev (minimax) approximation for pairwise comparison matrices that reduces to a linear program, with a consistency index characterized by the maximum cycle mean.'
date: 2026-07-01
venue: 'HCMUE Journal of Science (under review)'
citation: 'Thanh Nguyen, et al. (2026). &quot;Ranking Objects Based on Multiplicative Consistency of Comparison Matrices: Logarithmic Minimax (Chebyshev) Model and Applications.&quot; <i>HCMUE Journal of Science</i>. Under review.'
---

<!-- TODO: update the venue and date once the paper is accepted, and add paperurl / bibtexurl. -->

**Summary.** Given a pairwise comparison matrix that is not perfectly
consistent, ranking requires choosing an approximation criterion. This paper
studies the logarithmic Chebyshev (minimax) criterion, which controls the worst
deviation rather than the average one.

**What the paper does**

* Shows that the log-Chebyshev approximation of a pairwise comparison matrix
  reduces to a linear program, so the ranking is computable exactly.
* Introduces a consistency index $I_\infty$ and the associated factor
  $\kappa = e^{I_\infty}$, and characterizes it through the maximum cycle mean
  of an associated graph.
* Applies the model to two case studies: head-to-head records among the tennis
  "Big Four" ($n = 4$), and a ranking of the 13 attributes of the UCI Wine
  data set.

**Why it matters.** Minimax criteria give a worst-case guarantee on the
distortion introduced by an inconsistent comparison matrix, which is exactly
what a decision maker wants to bound. The linear-programming reduction makes
that guarantee cheap to obtain.
