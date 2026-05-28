---
layout: single
title: "Welcome!"
permalink: /
author_profile: true
---

Fields of interest : Health Economics,  Applied Microeconomics, Econometrics

**Why do people exercise or not exercise ?**

I am a health economist and applied microeconomist studying how insurance design, local resources, 
and policy incentives shape health behavior ( especially physical activity ) and health outcomes over 
the life cycle. My work combines quasi-experimental methods with rich survey and administrative data 
to answer questions at the intersection of health economics, economics of aging, and spatial inequality.
My projects speak directly to current policy debates on how to design incentives for 
healthy behavior among aging and vulnerable populations.

- **You can find my CV here : [CV](/files/Jung_CV.pdf)**




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

