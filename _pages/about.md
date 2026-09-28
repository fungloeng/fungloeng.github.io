---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# Bio
I am Feng Liang, a B.Eng. graduate in Electrical Engineering from Xi'an Jiaotong University.

[Resume (PDF)]({{ '/resume_fungloeng.pdf' | relative_url }})

# Publications

1. **Feng Liang**, Weixin Zeng, Runhao Zhao, and Xiang Zhao. [NeSTR: A Neuro-Symbolic Abductive Framework for Temporal Reasoning in Large Language Models](https://ojs.aaai.org/index.php/AAAI/article/view/40460). *Proceedings of the AAAI Conference on Artificial Intelligence*, 40(38):31907–31915, 2026.

2. Felicia T. Jiang, Runhao Zhao, **Feng Liang**, et al. [Structure-aware protein function prediction at isoform resolution](https://www.biorxiv.org/content/10.64898/2026.04.24.720502v2). *bioRxiv*, 2026.
