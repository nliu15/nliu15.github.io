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
## Working Papers

* __Gauges and Accelerated Optimization over Smooth and/or Strongly Convex Sets__  \
_Ning Liu, Benjamin Grimmer, Under Major Revision at Mathematical Programming, 2023, [Arxiv](https://arxiv.org/abs/2303.05037)_

* __On the Structure of Gauges of Weakly Convex and Weakly Concave Sets__  \
_Ning Liu, Benjamin Grimmer, 2024_


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
