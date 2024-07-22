---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
## Working Papers

* __Gauges and Accelerated Optimization over Smooth and/or Strongly Convex Sets__  \
_SIAM Conference on Optimization, Seattle, WA, 2023, _



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
