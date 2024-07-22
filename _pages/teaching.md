---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
## Courses TA'ed

* Introduction to Convexity  \hfill [2018]



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
