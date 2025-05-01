---
layout: archive
title: "Projects"
permalink: /research/projects/
author_profile: true
---

{% include base_path %}

A list of my academic publications.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}