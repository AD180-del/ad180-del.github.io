---
title: "Coursework Collection"
permalink: /coursework-collection/
---

Welcome to my coursework archive.

{% for item in site.coursework %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

