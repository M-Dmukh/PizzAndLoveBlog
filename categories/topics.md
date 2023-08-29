---
layout: page
title: Topics
---


{% for category in site.categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}"></div>
    <p></p>
    
    <h4><a href="{{ site.baseurl }}/categories/{{ category_name }}.html">{{ category_name | capitalize }}</a></h4>
  </div>
{% endfor %}