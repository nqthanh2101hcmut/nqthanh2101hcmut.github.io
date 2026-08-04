---
title: "Improving the Score Flow Matching Objective Function via Optimal Transport"
collection: publications
category: journals
permalink: /publication/2026-04-01-score-flow-matching-optimal-transport
excerpt: 'Uses optimal transport couplings to reshape the score flow matching objective, giving straighter probability paths, lower gradient variance and cheaper sampling.'
date: 2026-04-01
venue: 'HUFLIT Journal of Science'
citation: 'Thanh Nguyen, et al. (2026). &quot;Improving the Score Flow Matching Objective Function via Optimal Transport.&quot; <i>HUFLIT Journal of Science</i>.'
---

<!-- TODO: replace the date above with the exact issue date, and add volume/issue/pages to the citation. Add paperurl / bibtexurl once the official link is available. -->

**Summary.** Score flow matching learns a velocity field that transports a
simple reference distribution onto the data distribution. The coupling used to
pair source and target samples is a design choice, and an arbitrary one makes
the learned paths unnecessarily curved. This paper replaces it with an optimal
transport coupling and analyses what changes.

**What the paper does**

* Reformulates the score flow matching objective with an optimal transport
  coupling between the reference and data distributions.
* Analyses the effect on the geometry of the learned probability paths and on
  the variance of the training signal.
* Evaluates sample quality against the number of solver steps, so that the
  benefit is measured in compute rather than in epochs.

**Why it matters.** Straighter transport paths mean fewer integration steps at
inference time for the same sample quality, which is the practical bottleneck
for flow- and diffusion-based generation.
