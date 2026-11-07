---
layout: archive
title: "About me"
permalink: /
author_profile: true
---

{% include base_path %}

I am **Thanh Nguyen**, an applied mathematician from Ho Chi Minh City. I hold an
M.Res. in Applied Mathematics from the **Ho Chi Minh City University of
Technology (HCMUT), VNU-HCM**, where I worked with **Dr. Le Xuan Dai** and
ranked 1st in my cohort. My thesis, *Optimizing Score Flow Matching for
Generative Models Based on Density Estimation*, was graded 9.8/10.

My work has two threads. The first is **probabilistic machine learning and
generative modeling**: what a diffusion, score-based or flow-matching objective actually
estimates, how fast it can be learned, and how optimal transport can make it
cheaper to train and sample. The second is **robust learning under weak
supervision**, where I use tools such as unbalanced optimal transport to make
training objectives robust to labels that cannot be trusted.

I like problems where a clean piece of mathematics changes what a model actually
does in practice, and I am comfortable moving between a proof, a PyTorch or JAX
implementation, and the experiment that decides between them.

## Research interests

* **Probabilistic machine learning and generative modeling** — theory and
  algorithms for diffusion models, score and flow matching, and optimal
  transport.
* **Robust learning under weak supervision** — noisy-label sequence modeling
  and positive–unlabeled (PU) learning for recommendation.

## Currently looking for

I am seeking a **research internship or research scientist / research engineer
role in AI**. I am especially interested in
teams working on generative models, diffusion and flow-based methods, optimal
transport, or the theory–practice gap in modern deep learning. I am open to
positions abroad and to PhD opportunities in the same areas.

📄 [Download my CV (PDF)]({{ base_path }}/files/CV-Thanh_Nguyen.pdf) ·
✉️ [{{ site.author.email }}](mailto:{{ site.author.email }}) ·
🔗 [Google Scholar]({{ site.author.googlescholar }}) ·
💻 [GitHub](https://github.com/{{ site.author.github }})

## Selected work

{% assign selected_pubs = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_pubs %}
* **[{{ post.title }}]({{ base_path }}{{ post.url }})** — *{{ post.venue }}*{% unless post.category == "underreview" %}, {{ post.date | date: "%Y" }}{% endunless %}.
{% endfor %}

A full list is on the [publications page]({{ base_path }}/publications/), and
ongoing projects are described under [research]({{ base_path }}/portfolio/).

## News

* **Nov 2026** — *AlignBC: Learning from Noisy Transcripts with
  Alignment-Weighted Bounded Costs* submitted to *IJCAI 2027*.
* **Oct 2026** — *Derivative-Weighted Capacity Bounds for Kernel Score
  Estimation* accepted at the *NeurIPS 2026 Workshop BeNTo*.
* **Jun 2026** — Completed my M.Res. in Applied Mathematics at HCMUT; thesis
  graded 9.8/10.
* **Apr 2026** — *Improving the Score Flow Matching Objective Function via
  Optimal Transport* accepted in the *HUFLIT Journal of Science*.
* **Sep 2025** — Attended the Summer School on AI Agents, HUST, Hanoi.
* **Aug 2025** — Attended the 7th National Conference *Prob-Stats: Research,
  Application and Teaching*, Quy Nhon.
* **Jul 2025** — Attended the Summer School on Bayesian Models, Computation and
  Applications, Ho Chi Minh City.
* **Jun 2025** — Attended the Compute Ontario Summer School (online).
* **2025** — *Optimization of the Objective Function for Generative Models Based
  on Distribution Density Estimation* published in the *HCMUE Journal of
  Science*.
* **Oct 2024** — Started as a Graduate Research Assistant with Dr. Le Xuan Dai
  at HCMUT.

## Beyond research

I have taught international mathematics curricula (IGCSE, GCSE, IB, A-Level)
since 2021 and coached students for olympiads such as TIMO, HKIMO, SASMO, SEAMO,
AMC and ASMO (see [teaching]({{ base_path }}/teaching/) and
[mentoring]({{ base_path }}/mentoring/)). I also spent six months as a data science intern at PVCFC
(PetroVietnam), building analytics dashboards on operational and sales data.
