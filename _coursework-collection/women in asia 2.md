---
title: "Women in Asia: Part 1"
series: "Women in Asia"
layout: default
hidden: true
part: 2
---
{% assign essay_parts = site.coursework-collection | where: "series", "Women in Asia" | sort: "part" %}
{% assign current = page.part | minus: 1 %}
{% if essay_parts[current] %}
[Previous Part]({{ essay_parts[current].url }})
{% endif %}
{% assign next = page.part | plus: 1 | minus: 1 %}
{% if essay_parts[next] %}
[Next Part]({{ essay_parts[next].url }})
{% endif %}
