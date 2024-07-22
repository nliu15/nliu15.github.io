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
Education
======
B.S. in GitHub, GitHub University, 2012

M.S. in Jekyll, GitHub University, 2014
Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
