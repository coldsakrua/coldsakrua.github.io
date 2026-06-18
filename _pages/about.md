---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="home-intro">

<p class="home-intro__lead">
  I am a first-year graduate student at the <strong>School of Software &amp; Microelectronics</strong>, <a href="https://www.pku.edu.cn/">Peking University (PKU)</a>, advised by associate researcher <a href="https://nbic.pku.edu.cn/rcdw/kyry/02c5f5ce8e254b1e82a48bebd0a24c33.htm">Lei Ma (马雷)</a>.
  I received my bachelor's degree from the <strong>School of Electronics Engineering and Computer Science (EECS)</strong>, PKU (2021–2025).
</p>

</div>

## Research Interests

<div class="interest-tags">
  <span class="interest-tag">LLM Self-Distillation</span>
  <span class="interest-tag">Reinforcement Learning</span>
</div>

## Previous Research

<div class="interest-tags">
  <span class="interest-tag interest-tag--past">Spike Camera Reconstruction</span>
</div>

## Publications {#publications}

{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include home-publication.html %}
{% endfor %}

## Contact

Feel free to reach out via email: [ly0376@stu.pku.edu.cn](mailto:ly0376@stu.pku.edu.cn)
