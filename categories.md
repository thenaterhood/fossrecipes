---
layout: page
title: Categories
---
{% assign tags =  site.recipes | map: 'tags' | uniq | sort_natural %}
{% for tag in tags %}
  <h3 id="{{tag | slugify }}">{{ tag | upcase}}</h3>
  <ul>
  {% for r in site.recipes %}
    {% if r.tags contains tag %}
    <li><a href="{{ site.baseurl }}{{ r.url }}">{{ r.title }}</a></li>
    {% endif %}
  {% endfor %}
  </ul>
{% endfor %}
