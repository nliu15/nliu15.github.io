---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Conference Paper

- Poster: Hybrid Detection Mechanism for Spoofing Attacks in Bluetooth Low Energy Networks<br>**Hanlin Cai**, Yuchen Fang, Jiacheng Huang, Meng Yuan, Zhezhuang Xu<br>The 22nd ACM International Conference on Mobile Systems, Applications, and Services ([MobiSys 2024](https://www.sigmobile.org/mobisys/2024/))<br>Tokyo, Japan. June, 2024.

  <br>


---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
