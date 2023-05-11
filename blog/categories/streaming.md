---
layout: page
title: Streaming
---


{% for post in site.categories.streaming %}
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
  <div class="archive-group">
    <article class="archive-item">
    <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
  </div>
{% endfor %}