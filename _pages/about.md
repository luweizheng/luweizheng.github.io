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

I am a research engineer at the High-Performance Computing Center, Renmin University of China. I'm broadly interested in High-Performance Data Analysis, Data Science, and Machine Learning Systems. I am a technical evangelist, having authored articles and tutorials on diverse topics, including distributed computing (e.g. [Flink](https://lulaoshi.info/flink/), [Scalable Python](https://scale-py.godaai.org/)). Furthermore, I have published several books and delivered presentations at various industrial and academic conferences.

Before joining Renmin University, I had garnered years of experience working with some of the leading Chinese tech companies. For example, at [Xiaomi Inc.](https://en.wikipedia.org/wiki/Xiaomi) (小米), I held the position of Big Data Engineer, where I developed the recommendation system for the Xiaomi Browser.

## Research Interests

- **High-Performance Computing:** machine learning systems, high-performance AI systems
- **Data Science:** data science frameworks and tools, AI for data analysis

<strong style="color:#e74d3c">I am open to collaborations, feel free to reach out.</strong>


{% include_relative news.md %}

{% include_relative pub.md %}

{% include_relative book.md %}