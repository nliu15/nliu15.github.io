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

* __Introduction to Convexity__  <h3 align="right"> My latest Medium posts </h3>



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
