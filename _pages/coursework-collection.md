---
title: "Coursework Collection"
permalink: /coursework-collection/
---

Welcome to my coursework archive.

{% for item in site.coursework-collection %}
  - [{{ item.title }}]({{ item.url }})
{% endfor %}

