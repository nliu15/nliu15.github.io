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

* __On the Design of Novel Two-Phase Radial Methods__  \
_Ning Liu, Benjamin Grimmer, 2025_

* __On the Structure of Gauges of Weakly Convex and Weakly Concave Sets__  \
_Ning Liu, Benjamin Grimmer, 2024_

* __Gauges and Accelerated Optimization over Smooth and/or Strongly Convex Sets__  \
_Ning Liu, Benjamin Grimmer, Under Major Revision at Mathematical Programming, 2023_

## PhD Thesis
* __Gauges and Optimization over Structured Sets__  \
_Ning Liu_


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
