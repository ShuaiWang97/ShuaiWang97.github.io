---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Multimodal and Agentic AI, University of Amsterdam, Sep 2022 – present
* M.Sc in Artificial Intelligence (Cum Laude), University of Amsterdam, Sep 2020 – July 2022
* B.Eng in Aerospace Engineering, Shenyang Aerospace University, Sep 2015 – June 2019

Work Experience
======
* **Applied Scientist Intern** — Amazon, London, United Kingdom (Oct 2025 – Jan 2026)
  * Researched LLM alignment and safety by investigating conversational agent stereotyping and persona biases.
  * Developed evaluation frameworks for model perception and subjectivity in multi-turn dialogues, targeting an EMNLP 2026 submission.
  * Optimized agentic workflows to reduce stereotypical drift over long-context conversations.

* **Machine Learning Scientist Intern** — Booking.com, Amsterdam, Netherlands (July 2025 – Sep 2025)
  * Applied Supervised Fine-Tuning (SFT) on Meta DINOv3 to enhance geographic representations for large-scale hotel recommendation systems.
  * Achieved a +0.3% improvement in NDCG, Precision, and Recall on tens-million scale production benchmarks via advanced architecture optimization.
  * Collaborated with cross-functional teams to integrate specialized embeddings into the global hotel ranking stack.

Skills
======
* **Programming:** Python (PyTorch, NumPy, Pandas, Matplotlib, Scikit-Learn, SciPy, OpenCV), C++
* **Tools:** Git/GitHub, Command Line, LaTeX
* **Research Areas:** Agentic AI, LLM Agents, VLM Fine-tuning, Multimodal Retrieval, Graph Neural Networks, RAG
* **Languages:** English (Fluent), Dutch (A1), Chinese (Native)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
