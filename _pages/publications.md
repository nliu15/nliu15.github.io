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

* Gauges and Accelerated Optimization over Smooth and/or Strongly Convex Sets

Work experience
======
* Summer 2015: Research Assistant
  * Github University


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
