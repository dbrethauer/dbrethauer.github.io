---
layout: archive
permalink: /outreach/
title: "Outreach"
author_profile: true
---

Outreach is a vital part of any science career. Inspiring the next generation of scientists and ensuring that every, regardless of where they come from, has access to resources is the foundational bedrock of a just society. Furthermore, outreach brings to the forefront talent that might otherwise go unnoticed; a brilliant child may have no role models and not know what the job of being a scientist entails. Someone cannot aspire to be something they do not know about. As such, it is my mission to bring science to the public in an engaging format, to forge bonds between the community that I conduct my science in and bring the community into the fold of my work. Below are some of the Outreach events that I pursue.

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
