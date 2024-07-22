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
## Johns Hopkins University

* Nonlinear Optimization I , Fall 2021 (Teaching Assistant)
* Nonlinear Optimization II , Spring 2021 (Teaching Assistant)
* Combinatorial Optimization , Spring 2021 (Teaching Assistant)
* Numerical Linear Algebra, Fall 2020 (Teaching Assistant)
* Nonlinear Optimization II , Spring 2020 (Teaching Assistant)
* Financial Math Seminar , Fall 2019 (Teaching Assistant)
* Asymptotic Analysis , Fall 2019 (Teaching Assistant)
* Introduction to Control Theory and Optimal Control , Spring 2019 (Teaching Assistant)
* Reliability Analysis , Spring 2019 (Teaching Assistant)
* Introduction to Convexity, Fall 2018 (Teaching Assistant)
* Mathematical Modeling and Consulting, Fall 2018 (Teaching Assistant)


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
