---
layout: archive
permalink: /blog/
title: "Blog posts"
author_profile: true
---

{% include base_path %}

This page features short essays and reflections on topics related to mathematics and scientific computing, with some extensions to health, training, and personal insights.  

* Some Chinese-language posts are also shared via my WeChat public account, <br/><img src='/images/500x300.png'>
* Some English-language content is updated on [WordPress](/404/).


{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    ## {{ year }}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  - [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date: "%b %-d" }})</small>
{% endfor %}