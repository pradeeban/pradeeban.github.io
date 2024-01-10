---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
A few of my recent publications are given below. Please email me for collaboration if our research interests align.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
---
The full publications list can be found from [Google Scholar](https://scholar.google.com/citations?user=k1PYH8sAAAAJ&hl=en).
