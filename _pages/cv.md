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
* B.S. in Network Engineering, Wuhan University of Science and Technology, 2023–2027 (expected)
  * GPA: 3.58/4.0
  * Rank: 9/96 (Top 10%)
  * TOEFL iBT: 4.5/6.0 (new scale)

Research Experience
======
* Dec 2025 – Aug 2026: Undergraduate Research Assistant
  * Wuhan University of Science and Technology
  * Supervisor: Prof. Juanjuan He
  * **Spatial Complementary Consistency (SpaCon)**: Designed complementary dual-mask generation with smooth boundary regularization to address semantic boundary fragmentation. Outperformed competitive baselines in DSC on ACDC, LA, and Pancreas CT with only 5–10% labeled data. First author, PRICAI 2026 (Oral).
  * **Pseudo-Label Reliability Modeling (FCRE)**: Assisted in implementing a threshold-free co-training framework that jointly evaluates pseudo-label reliability via multi-subnetwork collaboration and feature distribution analysis. Co-authored manuscript under review at ESWA.

Selected Projects
======
* **Multi-Task Deep Learning for Clinical Comorbidity Prediction** · Core Modeler
  * 2nd Prize, APMCM, Sep 2025
  * Constructed a multi-task neural network to evaluate risks of stroke, heart disease, and cirrhosis using clinical parameters.
  * Applied association rule mining (Apriori/FP-Growth) to extract comorbidity patterns, bridging statistical data processing with deep learning.

* **IoT Pavement Water-Film Simulation & Hydroplaning Early Warning** · Co-Leader & Core Developer
  * Software Copyright Granted, Apr 2026
  * Developed a dynamic runoff simulation engine on 3D LiDAR point clouds (0.1 m spatial resolution) to evaluate real-time hydroplaning risk.
  * Implemented multi-objective optimization algorithms and a Streamlit UI to automate grooving and maintenance planning.

Honors & Awards
======
* Honorable Mention, MCM/ICM 2026
* 1st Prize (Provincial), National Statistical Modeling Contest 2025
* 2nd Prize, Asia and Pacific Mathematical Contest in Modeling (APMCM) 2025
* 3rd Prize, National University Network Technology Challenge 2026
* Second-Class Academic Scholarship (Top 7%), WUST 2026

Technical Skills
======
* **Languages & Tools**: Python (PyTorch, NumPy, Pandas), C/C++, Linux, Git, CUDA, LaTeX, Streamlit
* **Research Interests**: Semi-Supervised Learning, Medical Image Segmentation, Multimodal Learning, Diffusion Models

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--
To display SpaCon under Publications, create _publications/2026-11-01-spacon.md with the following front matter:

---
title: "SpaCon: Spatial Complementary Consistency for Semi-Supervised Medical Image Segmentation"
collection: publications
category: conferences
permalink: /publication/2026-11-01-spacon
excerpt: 'A complementary dual-mask consistency framework for semi-supervised 3D medical image segmentation, learning from only 5–10% labeled data.'
date: 2026-11-01
venue: 'PRICAI 2026 (Oral)'
paperurl: ''
citation: 'Shiqi Shi, Zhengshi Chen, and Juanjuan He. (2026). "SpaCon: Spatial Complementary Consistency for Semi-Supervised Medical Image Segmentation." <i>PRICAI 2026</i>. Oral presentation (long paper track).'
---
-->

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>


Service and Leadership
======
<!-- Remove this section if you have no relevant experience. Otherwise replace with actual roles. -->