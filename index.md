---
layout: single
title: "Welcome!"
permalink: /
author_profile: true
---

Fields of interest : Health Economics,  Applied Microeconomics, Econometrics

I am a health economist and applied microeconomist studying how insurance design, local resources, 
and policy incentives shape health behavior ( especially physical activity ) and health outcomes over 
the life cycle. My work combines quasi-experimental methods with rich survey and administrative data 
to answer questions at the intersection of health economics, economics of aging, and spatial inequality.


- You can find my CV here : [CV](/files/Jung_CV.pdf)

  
In ongoing and completed projects, I study:
- **How Medicare Advantage (MA) fitness benefits affect seniors’ physical activity?**
- **How social networks and geography shape MA enrollment and program uptake?**
- **What are the facilitators and barriers to exercise?**
- **How emerging technologies such as digital health tools, wearable devices shape peventive health behavior?**
- **How place-based resources, such as food assistance programs and neighborhood environments, influence health?**

Together, these projects speak directly to current policy debates on how to design incentives for 
healthy behavior among aging and vulnerable populations.



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

