---
layout: page
title: All Recipes
---
<ul>
{% for r in site.recipes %}
<li>
<a href="{{ site.url }}{{ r.url }}">{{ r.title }}</a>
</li>
{% endfor %}
</ul>
