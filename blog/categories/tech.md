---
layout: page
title: Tech
---


{% for post in site.categories.tech %}
  <div class="archive-group">
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
  </div>
{% endfor %}