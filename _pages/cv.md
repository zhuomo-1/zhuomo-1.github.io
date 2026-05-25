---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of my CV is available [here](/files/cv_haoyu_wang.pdf).

Education
======
* **M.S. in Electronic Information Technology**, Beijing Jiaotong University (BJTU), Sept. 2023 – Jun. 2026 (expected)
  * School of Computer Science and Technology
* **B.Eng. in Robotics Engineering**, Guilin University of Electronic Technology (GUET), Sept. 2019 – Jun. 2023
  * School of Artificial Intelligence

Research Interests
======
* **Neurosymbolic AI** — coupling symbolic / logical priors with deep perception; video event understanding under structured constraints; self-supervised spatiotemporal representations as a substrate for neurosymbolic reasoning.
* **Generative models and controllable editing** — diffusion inversion, disentangled semantic manipulation, training- and tuning-free image editing.
* **Robust perception** — long-tailed, few-shot, and dual-view detection, with a focus on X-ray security inspection.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **Algorithm research on real-world X-ray prohibited-item detection.** Prior-aware debiasing for severe head/tail class imbalance; few-shot continual learning for emerging object categories without catastrophic forgetting. Outputs: first-authored manuscripts under review at IEEE TIFS and NeurIPS 2026.

Honours & Awards
======
* **First-Class Academic Scholarship**, BJTU — 2023, 2024, 2025 (three consecutive years)
* **Outstanding Bachelor's Thesis Award** (school-level), School of Artificial Intelligence, GUET, 2023
* **Outstanding Completion** (highest rating), Provincial Undergraduate Innovation Program

Technical Skills
======
* **Languages**: Python, C/C++, MATLAB, Bash, LaTeX
* **Frameworks**: PyTorch, Hugging Face Diffusers & Transformers, MMDetection, CUDA
* **Tools**: Linux / SSH / tmux, Git, Docker, Weights & Biases, Blender
* **Research competences**: diffusion models and inversion; object detection under long-tailed / out-of-distribution regimes; neurosymbolic learning; video event understanding.
