---
layout: default
title: All terms
---

{% for term in site.terms %}
<h2><a href="{{ term.url }}">{{ term.title }}</a></h2>
{% endfor %}
