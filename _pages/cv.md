---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/CV-Thanh_Nguyen.pdf" class="btn btn--primary">Download CV as PDF</a>

Applied mathematician working on the theory and methods of generative models
and on learning under weak or noisy supervision. Currently seeking an **AI
research internship or research scientist / research engineer position**.

Education
======
* **M.Res. in Applied Mathematics**, Ho Chi Minh City University of Technology (HCMUT), VNU-HCM, 2024–2026
  * GPA: 3.5/4.0 (≈ 8.42/10)
  * Thesis: *Optimizing Score Flow Matching for Generative Models Based on Density Estimation* (grade 9.8/10)
  * Advisor: Dr. Le Xuan Dai
* **B.Sc. in Mathematics Education** (second degree, part-time), Dalat University, 2024–2026
  * GPA: 3.2/4.0
* **B.Sc. in Finance & Banking**, University of Economics Ho Chi Minh City, 2020–2023
  * GPA: 3.2/4.0

Research interests
======
* **Generative models (theory & methods):** diffusion, score-based and flow matching models; optimal transport and Schrödinger bridges; density-estimation-based objectives
* **Weak supervision:** PU learning for recommender systems; unbalanced OT for robust CTC

Research experience
======
* **AlignBC: Bounded-Cost Supervision for CTC Training**, Mar 2026 – present
  * Developed AlignBC, a training-only framework that adds alignment-weighted bounded costs to CTC-family objectives using posterior or unbalanced OT plans, without changing the decoder or inference
  * Derived closed-form gradient updates and proved a mass–sensitivity factorization; achieved significant WER reductions in 7 of 8 CRNN-based STC/OTC comparisons on IAM and UIT-HWDB under synthetic transcript noise (five seeds; Holm-corrected tests)

* **Capacity-Dependent Theory for Kernel Score Estimation**, Jan 2026 – Aug 2026
  * Introduced a derivative-weighted effective dimension for kernel score estimation, giving rates $\widetilde{O}_P(M^{-(r+1/2)/(2r+1+\alpha)})$ beyond capacity-independent bounds
  * Proved an exact derivative penalty $2/A$ for diagonal and curl-free torus kernels and a matching minimax lower bound, with guarantees holding at every diffusion time

* **Graduate Research Assistant**, Department of Applied Mathematics, HCMUT – VNU-HCM, Oct 2024 – Mar 2026
  * Advisor: Dr. Le Xuan Dai
  * *Generative models* (2025–2026): proposed objectives unifying KL, score and flow matching, and an OT-improved score flow matching objective (2 journal papers, M.Res. thesis)
  * *Bayesian optimization* (2024–2025): benchmarked Bayesian optimization for hyperparameter search

Publications and manuscripts
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Industry experience
======
* **Data Scientist Intern**, PVCFC – PetroVietnam, Oct 2024 – Apr 2025
  * Extracted and cleaned operational and sales data from ERP systems to improve data quality and consistency
  * Built Power BI dashboards for revenue, production and sales monitoring, supporting data-driven decisions and reducing excess inventory by approximately 5%

Skills
======
* **Programming:** Python (PyTorch, JAX, NumPy, SciPy, scikit-learn, Matplotlib), R; GPU-parallel training
* **Mathematical and ML foundations:** probability, mathematical statistics, optimization, ODEs, optimal transport, numerical methods; score/flow matching, kernel methods and generative modelling
* **Research tools:** Git, Linux/Unix, LaTeX, Jupyter Notebook, manuscript preparation, experiment tracking and visualization
* **Languages:** Vietnamese (native), English (professional working proficiency)

Academic programs
======
* **Summer School on AI Agents**, HUST, Hanoi, Vietnam — Sep 08–12, 2025
* **The 7th National Conference "Prob-Stats: Research, Application and Teaching"**, Quy Nhon, Vietnam — Aug 04–08, 2025
* **Summer School on Bayesian Models, Computation and Applications**, Ho Chi Minh City, Vietnam — Jul 23 – Aug 01, 2025
* **Compute Ontario Summer School**, online — Jun 02–20, 2025
* **Spring School on Statistics and Machine Learning**, HCMUS – VNU-HCM, Vietnam — Apr 08–18, 2025

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% if site.mentoring.size > 0 %}
Mentoring
======
  <ul>{% for post in site.mentoring reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}

Professional certificates
======
* IBM Machine Learning Professional Certificate — IBM
* IBM Data Science Professional Certificate — IBM
* Machine Learning / Deep Learning Specialization — DeepLearning.AI
* Mathematics for Machine Learning and Data Science — DeepLearning.AI

Service
======
* Volunteer work with NGOs and iVolunteer, including seasonal blood donation drives and community meal support

References
======
* **Dr. Le Xuan Dai** — Department of Applied Mathematics, HCMUT – VNU-HCM · ytkadai@hcmut.edu.vn
* **Assoc. Prof. Dr. Huynh Thi Hong Diem** — Department of Applied Mathematics, HCMUT – VNU-HCM · hthdiem@hcmut.edu.vn
