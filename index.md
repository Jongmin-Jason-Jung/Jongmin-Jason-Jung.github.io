---
layout: single
title: "Welcome!"
permalink: /
author_profile: true
---

Fields of interest : Health Economics,  Applied Microeconomics, Econometrics

My research integrates applied microeconomics and health economics to examine how policy and program design shape physical activity and health outcomes among older adults. 
Using microeconometric methods, I study the determinants of fitness program uptake and the causal effects of Medicare Advantage fitness benefits on seniors’ health behaviors.

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

