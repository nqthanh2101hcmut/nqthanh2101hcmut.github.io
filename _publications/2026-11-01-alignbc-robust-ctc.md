---
title: "AlignBC: Learning from Noisy Transcripts with Alignment-Weighted Bounded Costs"
collection: publications
category: underreview
selected: true
permalink: /publication/2026-11-01-alignbc-robust-ctc
redirect_from:
  - /publication/2026-09-15-alignbc-robust-ctc
excerpt: 'A training-only framework that adds alignment-weighted bounded costs to CTC-family objectives, using posterior or unbalanced optimal transport plans, to make CTC training robust to noisy transcripts without changing the decoder or inference.'
date: 2026-11-01
venue: 'Submitted to IJCAI 2027'
citation: 'Thanh Nguyen, et al. &quot;AlignBC: Learning from Noisy Transcripts with Alignment-Weighted Bounded Costs.&quot; Submitted to <i>IJCAI 2027</i>.'
---

<!-- TODO: update venue/date when the decision is out; add paperurl (e.g. arXiv) if you post a preprint. -->

**Summary.** Connectionist Temporal Classification (CTC) assumes the target
transcript is correct. When transcripts are noisy, the loss forces the model to
align to wrong labels. AlignBC changes only the *training objective*: it adds an
alignment-weighted, bounded cost on top of CTC-family losses, so that a
corrupted label cannot dominate the gradient.

**What the paper does**

* Introduces **AlignBC**, a training-only framework that adds alignment-weighted
  bounded costs to CTC-family objectives. The alignment weights come either
  from the CTC posterior or from an **unbalanced optimal transport** plan.
* Leaves the decoder and the inference procedure unchanged, so it can be added
  to an existing CTC pipeline without touching deployment.
* Derives closed-form gradient updates and proves a **mass–sensitivity
  factorization** of the resulting objective.
* Reports significant WER reductions in **7 of 8** CRNN-based STC/OTC
  comparisons on **IAM** and **UIT-HWDB** under synthetic transcript noise
  (five seeds; Holm-corrected significance tests).

**Why it matters.** Large handwriting and speech corpora are rarely clean.
A fix that lives entirely in the loss, with guarantees on how much any single
bad label can move the model, is cheap to adopt.
