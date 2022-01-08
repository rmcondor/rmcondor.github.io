---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Programming language
* **Maps in R**: I developed a guide where I show how to create maps in R. The guide use the National Household Survey of Peru and is currently in Spanish.

* **econresearchR package**: A useful R package for organizing files in economics applied research. You can see the instructions to install it [here](https://github.com/rmcondor/econresearchR).

* **Stata schemes**: I contributed in the creation of two official Stata schemes.
  * IPA: Called [*ipaplots*](https://github.com/PovertyAction/ipaplots)
  * La Rotonda: Called [*blogrotonda*](https://github.com/La-Rotonda/blogrotonda)

