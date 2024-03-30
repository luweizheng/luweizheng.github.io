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

I am a research engineer at the High-Performance Computing Center, Renmin University of China. I'm broadly interested in Machine Learning Systems, Data Science, and Data Management Systems. I am also a technical writer. I have written articles and tutorials on various topics including distributed computing (e.g. [Flink](https://lulaoshi.info/flink/), [Distributed Python](https://godaai.github.io/distributed-python-en/)), and Deep Learning.

Previously, I was a Big Data Engineer at [Xiaomi Inc.](https://en.wikipedia.org/wiki/Xiaomi) (小米集团), where I built the recommendation system for the Xiaomi Browser. Before that, I served [Zhipin](https://finance.yahoo.com/quote/BZ) (BOSS直聘), the premier online recruitment platform in China. My academic background includes a Master's degree from Peking University and a Bachelor's degree from Beijing University of Posts and Telecommunications.

## Research Interests

- **High-Performance Computing:** machine learning systems, high-performance AI systems
- **Data Science:** data science frameworks and tools, large model for data analysis

<strong style="color:#e74d3c">I am open to collaborations, feel free to reach out.</strong>


{% include_relative news.md %}

{% include_relative pub.md %}

{% include_relative book.md %}