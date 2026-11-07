---
title: "AlignBC: learning from noisy transcripts"
excerpt: "A training-only framework that makes CTC-family objectives robust to noisy transcripts using alignment-weighted bounded costs from posterior or unbalanced optimal transport plans."
collection: portfolio
period: "Mar 2026 – present"
status: "Submitted to IJCAI 2027 (Nov 2026) — under review, paper not yet available"
---

**Role:** First author · **Mar 2026 – present** · Manuscript submitted to IJCAI 2027

### The question

CTC training trusts the transcript. When a fraction of the labels are wrong,
the loss still pushes the model to align with them, and the damage grows with
the noise level. Can robustness be obtained by changing *only* the training
objective, without touching the decoder or inference?

### What I did

* Developed **AlignBC**, which adds alignment-weighted bounded costs to
  CTC-family objectives. The alignment weights come from the CTC posterior or
  from an **unbalanced optimal transport** plan, so mass can be left
  unmatched where the transcript is likely wrong.
* Derived closed-form gradient updates and proved a **mass–sensitivity
  factorization** that makes explicit how much a corrupted label can move
  the model.
* Ran a controlled evaluation on **IAM** and **UIT-HWDB** with CRNN-based
  STC/OTC baselines under synthetic transcript noise: five seeds per setting
  and Holm-corrected significance tests. AlignBC gives significant WER
  reductions in **7 of 8** comparisons.

### Output

*AlignBC: Learning from Noisy Transcripts with Alignment-Weighted Bounded Costs*,
submitted to IJCAI 2027.

**Tools:** Python, PyTorch, GPU-parallel training, OT solvers.
