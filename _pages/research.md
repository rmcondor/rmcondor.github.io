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

## Publications
* Campos, G. y Condor, R. (2022). Ethnicity in Peru and its multidimensional nature: a proposal for measurement. Desde el Sur, 14(1), e00012 [(Original in Spanish)](https://revistas.cientifica.edu.pe/index.php/desdeelsur/article/view/1030/961)

## Work in progress
* The effect of trade openness on wage inequality: evidence from Peru