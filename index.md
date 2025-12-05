---
layout: single
title: "Welcome!"
permalink: /
author_profile: true
---

Fields of interest : Health Economics,  Applied Microeconomics, Econometrics

My research applies microeconometric methods to evaluate how health-policy and program design shape physical activity and health outcomes among older adults. I study the behavioral and structural determinants of fitness-benefit uptake and estimate the causal impacts of Medicare Advantage fitness programs and related health-promotion initiatives on seniors’ exercise behavior and healthy aging.

- CV: [download](/files/Jung_CV.pdf)

<h2>Conference / Seminar Presentations</h2>
<ul>
  {% assign talks = site.posts | where_exp: "p","p.categories contains 'talks'" %}
  {% for post in talks %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {% if post.location %}
      — {{ post.location }}
      {% endif %}
    </li>
  {% endfor %}
</ul>

