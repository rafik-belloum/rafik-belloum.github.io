---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

About me
======

Hi, I'm Rafik. I'm maître de conférences (~associate professor) in Computer Science at Université Polytechnique Hauts-de-France, and a member of the LAMIH laboratory (UMR CNRS 8201).

I conduct research in Human-Computer Interaction (HCI) to support the design and use of intelligent systems that are better aligned with human needs. My work focuses on providing methods, tools, and interfaces for both system designers and end users.

I follow a user-centered approach that combines need analysis, iterative design, and evaluation, using both qualitative and quantitative methods. I apply this work in areas such as smart home technologies for older adults and explainable artificial intelligence (XAI).

Selected Publications
======

{% for post in site.publications limit:4 %}
<div class="publication-card">
  <div class="pub-badge">{{ post.venue }}</div>
  <p><strong>{{ post.title }}</strong><br/>
  {{ post.authors }}<br/>
  <em>{{ post.venue }}</em></p>
</div>
{% endfor %}
