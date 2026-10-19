---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

I am a Ph.D. student at the School of Information Science and Technology, [University of Science and Technology of China (USTC)](https://en.ustc.edu.cn/). My research focuses on LLM post-training, agents, reinforcement learning, and world models.

Education
======
{% include profile-education.html %}

Research Experience
======
{% include profile-experience.html %}

Selected Publications
======
{% include profile-publications.html %}

Honors and Awards
======
<ul>
  {% for honor in site.data.profile.honors %}
    <li>{{ honor }}</li>
  {% endfor %}
</ul>

Contact
======
- [Email](mailto:{{ site.author.email }})
- [Google Scholar]({{ site.author.googlescholar }})
- [GitHub](https://github.com/{{ site.author.github }})
