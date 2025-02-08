---
title: "Machine Learning Systems are Bloated and Vulnerable"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Today's software is bloated with both code and features that are not used by most users.'
date: 2022-12-01
venue: 'ACMSigmetrics'
paperurl: 'https://arxiv.org/abs/2212.09437'
citation: 'Huaifeng Zhang, Fahmi Abdulqadir Ahmed, Dyako Fatih, Akayou Kitessa, Mohannad Alhanahnah, Philipp Leitner, Ahmed Ali-Eldin
 (2022) Machine Learning Systems are Bloated and Vulnerable'
---

Today's software is bloated with both code and features that are not used by most users. This bloat is prevalent across the entire software stack, from operating systems and applications to containers. Containers are lightweight virtualization technologies used to package code and dependencies, providing portable, reproducible and isolated environments. For their ease of use, data scientists often utilize machine learning containers to simplify their workflow. However, this convenience comes at a cost: containers are often bloated with unnecessary code and dependencies, resulting in very large sizes. In this paper, we analyze and quantify bloat in machine learning containers. We develop MMLB, a framework for analyzing bloat in software systems, focusing on machine learning containers. MMLB measures the amount of bloat at both the container and package levels, quantifying the sources of bloat. In addition, MMLB integrates with vulnerability analysis tools and performs package dependency analysis to evaluate the impact of bloat on container vulnerabilities. Through experimentation with 15 machine learning containers from TensorFlow, PyTorch, and Nvidia, we show that bloat accounts for up to 80% of machine learning container sizes, increasing container provisioning times by up to 370% and exacerbating vulnerabilities by up to 99%.
