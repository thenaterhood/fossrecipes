---
layout: page
title: All Recipes
---
{% assign sorted =  site.recipes | sort_natural: "title" %}
<ul>
{% for r in sorted %}
<li>
<a href="{{ site.url }}{{ r.url }}">{{ r.title }}</a>
</li>
{% endfor %}
</ul>
