---
layout: archive
title: "About me"
permalink: /
author_profile: true
---

{% include base_path %}

I am **Thanh Nguyen**, an M.Res. student in Applied Mathematics at the
**Ho Chi Minh City University of Technology (HCMUT), VNU-HCM**, advised by
**Dr. Le Xuan Dai**.

My work sits at the intersection of **mathematical machine learning, generative
modeling, and optimal transport**. I study how the *training objective* of a
generative model is built: what it estimates, how it is discretized, and what
that implies for sampling efficiency, stability, and robustness. My thesis,
*Optimizing Score Flow Matching for Generative Models Based on Density
Estimation*, develops a density-estimation view that connects KL minimization
with score-matching and flow-matching objectives, and tests the resulting
formulations empirically.

I like problems where a clean piece of mathematics changes what a model actually
does in practice, and I am comfortable moving between a proof, a PyTorch
implementation, and the experiment that decides between them.

## Research interests

* **Generative modeling** — diffusion and score-based models, normalizing flows,
  flow matching, variational autoencoders.
* **Objective design and density estimation** — what different training losses
  estimate, and how objective choice affects convergence and sample quality.
* **Optimal transport and Schrödinger bridges** — OT-based couplings for
  straighter probability paths and cheaper sampling.
* **Numerical discretization and sampling efficiency** — solver choice, step
  budgets, and the error they introduce.
* **Robustness** — training under noisy or misspecified supervision.
* **Adjacent interests** — Bayesian optimization, decision models and ranking
  from pairwise comparison matrices.

## Currently looking for

I am seeking a **research internship or research scientist / research engineer
role in AI**, starting after my M.Res. (2026). I am especially interested in
teams working on generative models, diffusion and flow-based methods, optimal
transport, or the theory–practice gap in modern deep learning. I am open to
positions abroad and to PhD opportunities in the same areas.

📄 [Download my CV (PDF)]({{ base_path }}/files/CV-Thanh_Nguyen.pdf) ·
✉️ [{{ site.author.email }}](mailto:{{ site.author.email }}) ·
🔗 [Google Scholar]({{ site.author.googlescholar }}) ·
💻 [GitHub](https://github.com/{{ site.author.github }})

## Selected work

{% assign recent_pubs = site.publications | sort: "date" | reverse %}
{% for post in recent_pubs limit:3 %}
* **[{{ post.title }}]({{ base_path }}{{ post.url }})** — *{{ post.venue }}*, {{ post.date | date: "%Y" }}.
{% endfor %}

A full list is on the [publications page]({{ base_path }}/publications/), and
ongoing projects are described under [research]({{ base_path }}/portfolio/).

## News

* **2026** — Manuscript on ranking from pairwise comparison matrices
  (logarithmic minimax / Chebyshev model) submitted to the *HCMUE Journal of
  Science*; under review.
* **2026** — *Improving the Score Flow Matching Objective Function via Optimal
  Transport* accepted in the *HUFLIT Journal of Science*.
* **Sep 2025** — Attended the Summer School on AI Agents, HUST, Hanoi.
* **Aug 2025** — Attended the 7th National Conference *Prob-Stats: Research,
  Application and Teaching*, Quy Nhon.
* **Jul 2025** — Attended the Summer School on Bayesian Models, Computation and
  Applications, Ho Chi Minh City.
* **Jun 2025** — Attended the Compute Ontario Summer School (online).
* **2025** — *Optimization of the Objective Function for Generative Models Based
  on Distribution Density Estimation* published in the *HCMUE Journal of
  Science*.
* **Mar 2025** — Started as a Graduate Research Assistant on density-estimation
  based objective design for generative models.

## Beyond research

I have taught international mathematics curricula (IGCSE, GCSE, IB, A-Level)
since 2021 and coached students for olympiads such as TIMO, HKIMO, SASMO, SEAMO,
AMC and ASMO. I also spent six months as a data science intern at PVCFC
(PetroVietnam), building analytics dashboards on operational and sales data.
