---
title: "Optimal transport couplings for score flow matching"
excerpt: "Replacing the independent coupling in score flow matching with an optimal transport coupling: straighter probability paths, lower-variance training signal, and fewer solver steps at inference."
collection: portfolio
period: "2025 – 2026"
status: "Accepted in HUFLIT Journal of Science (Apr 2026)"
redirect_from:
  - /portfolio/02-optimal-transport-flow-matching/
---

**Role:** Graduate Research Assistant, HCMUT (VNU-HCM) · **2025 – 2026**

### The question

Flow matching learns a velocity field that pushes a reference distribution onto
the data distribution. Training pairs a source sample with a target sample, and
the pairing is a free choice. An arbitrary pairing produces curved probability
paths, and curved paths cost integration steps at sampling time.

### What I did

* Reformulated the score flow matching objective using an optimal transport
  coupling instead of an independent one.
* Analysed how the coupling changes the geometry of the learned paths and the
  variance of the regression target.
* Benchmarked sample quality *against the number of solver steps*, so that any
  improvement is measured in inference compute, not in training epochs.

### Output

*Improving the Score Flow Matching Objective Function via Optimal Transport*
(HUFLIT Journal of Science, 2026). This line of work also motivates my current
interest in Schrödinger bridges as the stochastic counterpart of the same idea.

**Tools:** Python, PyTorch, POT-style OT solvers, NumPy, Matplotlib.
