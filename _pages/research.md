---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in progress

* Ethnic inequality: a look from Peruvian microdata (with Guiliana Campos)
* The effect of trade openness on poverty and inequality in Peru: a micro-simulation analysis