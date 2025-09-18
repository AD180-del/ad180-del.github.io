---
title: "Women in Asia: Introduction"
series: "Women in Asia"
layout: default
hidden: true
part: 1
---
{% assign essay_parts = site.coursework-collection | where: "series", "Women in Asia" | sort: "part" %}
{% assign current_index = page.part | minus: 1 %}

{% assign previous_index = current_index | minus: 1 %}
{% if previous_index >= 0 and essay_parts[previous_index] %}
[Previous Part]({{ essay_parts[previous_index].url }})
{% endif %}

{% assign next_index = current_index | plus: 1 %}
{% if next_index < essay_parts.size and essay_parts[next_index] %}
[Next Part]({{ essay_parts[next_index].url }})
{% endif %}


