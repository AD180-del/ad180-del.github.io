---
title: "Coursework Collection"
permalink: /coursework-collection/
---

Welcome to my coursework archive.

{% for item in site.coursework-collection %}
  {% if item.series == nil and item.hidden != true %}
    - [{{ item.title }}]({{ item.url }})
  {% endif %}
{% endfor %}


