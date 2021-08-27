---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Workshops
======
* Ensemble Machine Learning System for Student Academic Performance Prediction. **Yinkai Wang\***, Kaiyi Guan\*, Aowei Ding\*, Yuanqi Du. Research Paper in Workshop for Undergraduates in Educational Data Mining and Learning Engineering (W4U) @EDM 2021.
