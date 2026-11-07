---
title: "Bayesian optimization for machine learning models"
excerpt: "A study of acquisition strategies and training dynamics to identify where conventional Bayesian optimization breaks down in high-dimensional hyperparameter and architecture search."
collection: portfolio
redirect_from:
  - /portfolio/03-bayesian-optimization/
---

**Role:** Graduate Research Assistant, HCMUT (VNU-HCM) · **Advisor:** Dr. Le Xuan
Dai · **Oct 2024 – Mar 2025**

### The question

Bayesian optimization is the default answer for expensive black-box tuning, but
its guarantees weaken as dimension grows — which is exactly the regime of deep
learning hyperparameter and architecture search.

### What I did

* Studied Bayesian optimization methods and their applicability to
  hyperparameter and architecture optimization in deep learning.
* Analysed acquisition strategies, training dynamics and model characteristics
  to isolate the failure modes of conventional Bayesian optimization in
  high-dimensional settings.
* Evaluated candidate algorithmic improvements on benchmark datasets and
  documented the methodology and findings in research reports.

### Why it still matters to me

The experience shaped how I approach objective design: an optimizer can only be
as good as the surface it is given, so it is usually more productive to fix the
objective than to fix the search.

**Tools:** Python, scikit-learn, PyTorch, NumPy, SciPy.
