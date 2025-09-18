---
permalink: /irinpopculture/
title: "IR in Pop Culture"
---

Welcome to "IR in Pop Culture". This series of short articles aims to explain concepts from IR with the help of pop culture.

<h2> Articles</h2>
{% for post in site.categories["IR in Pop Culture"] %}
  [{{ post.title }}]({{ post.url }})
  {{ post.date | date: "%B %d, %Y" }}
  {{ post.excerpt }}
{% endfor %}

