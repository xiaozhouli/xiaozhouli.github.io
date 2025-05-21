---
layout: archive
title: "Projects"
permalink: /research/projects/
author_profile: true
---



{% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %}