---
layout: archive
permalink: /blog/
title: "Blog posts"
author_profile: true
---

{% include base_path %}

This page features short essays and reflections on topics related to mathematics and scientific computing — with some extensions to health, training, and personal insights.  
Some Chinese-language posts are also shared via my WeChat public account, while some English-language content is updated on [WordPress](/404/).

{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}