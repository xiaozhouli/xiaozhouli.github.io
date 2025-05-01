---
layout: archive
title: "Publications"
permalink: /research/publications/
author_profile: true
---

{% include base_path %}

A list of my academic publications.

{% for post in site.publications reversed %}
  {% include archive-single-cite.html %}
{% endfor %}