---
title: "Ranking from pairwise comparison matrices: a logarithmic minimax model"
excerpt: "A log-Chebyshev approximation of inconsistent pairwise comparison matrices that reduces to a linear program, with a consistency index characterized by the maximum cycle mean."
collection: portfolio
---

**Role:** Author · **2025 – 2026** · Manuscript under review

### The question

Real pairwise comparison matrices are never perfectly consistent. Most ranking
methods minimize an average deviation; a decision maker often cares about the
*worst* deviation instead.

### What I did

* Formulated the ranking problem as a logarithmic Chebyshev (minimax)
  approximation of the comparison matrix, and showed that it reduces to a
  linear program — so the solution is exact and cheap.
* Defined a consistency index $I_\infty$ with factor $\kappa = e^{I_\infty}$ and
  characterized it via the maximum cycle mean of an associated graph.
* Validated the model on two applications: head-to-head records among the tennis
  "Big Four", and a ranking of the 13 attributes of the UCI Wine data set.

### Output

*Ranking Objects Based on Multiplicative Consistency of Comparison Matrices:
Logarithmic Minimax (Chebyshev) Model and Applications*, submitted to the HCMUE
Journal of Science (2026), under review.

**Tools:** Python, linear programming solvers, R.
