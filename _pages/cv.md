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
* M.S. in Data Science, Fordham University, 2026 (expected)
* B.Sc. in Software Engineering, Addis Ababa University, 2022

Work experience
======
* August 2024 - Present: Research Assistant
  * Fordham University
  * Duties includes: Working on utilizing Large Language Models(LLMs) for medical purposes, currently fine-tuning LLMs, and combining them with other traditional machine learning models to predict Multiple Sclerosis relapse.
  * Supervisor: Dr. [Yijun Zhao](https://storm.cis.fordham.edu/~yzhao/)

* Sepember 2022 - August 2024: Software Engineer
  * Turing Inc.
  * Duties included: Contributed to OpenAI's ChatGPT project, specifically on generating datasets for training the 'code interpreter' feature.

Skills
======
* Python
  * PyTorch
  * Scikit-learn
* Java
* SQL
* Hadoop
* Tableau

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>