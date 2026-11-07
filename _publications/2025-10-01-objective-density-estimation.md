---
title: "Optimization of the Objective Function for Generative Models Based on Distribution Density Estimation"
collection: publications
category: journals
selected: true
permalink: /publication/2025-10-01-objective-density-estimation
excerpt: 'A density-estimation view of generative training objectives that links KL minimization to score-matching and flow-matching losses, with a comparative study of convergence, stability and sample quality.'
date: 2025-10-01
venue: 'HCMUE Journal of Science'
citation: 'Thanh Nguyen, et al. (2025). &quot;Optimization of the Objective Function for Generative Models Based on Distribution Density Estimation.&quot; <i>HCMUE Journal of Science</i>.'
---

<!-- TODO: replace the date above with the exact issue date, and add volume/issue/pages to the citation. Add paperurl / bibtexurl once the official link is available. -->

**Summary.** Training a generative model means choosing what quantity the loss
estimates. This paper takes distribution density estimation as the starting
point and derives a formulation that makes the relationship between KL
minimization, score matching and flow matching explicit, rather than treating
them as separate recipes.

**What the paper does**

* Formulates the training objective of diffusion models, normalizing flows and
  variational autoencoders in a single density-estimation framework.
* Shows how the resulting objective specializes to score-matching and
  flow-matching losses under different modelling choices.
* Compares the formulations empirically on convergence behaviour, training
  stability and sample quality.

**Why it matters.** Objective design is one of the few places where a change of
a few terms in a loss changes the entire training dynamic. Treating the loss as
a density-estimation problem gives a principled way to decide between
alternatives instead of tuning them blindly.
