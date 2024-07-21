---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
My current research focuses on the design and analysis of algorithms for continuous optimization problems beyond the areas where classical theory applies. I am interested in the intersection of data science, stochastic optimization and continuous optimization.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
