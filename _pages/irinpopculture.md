---
permalink: /irinpopculture/
title: "IR in Pop Culture"
---

Welcome to "IR in Pop Culture". This series of essays aims to explain concepts from IR with the help of pop culture.

<h2>Pop Culture Articles</h2>
{% for post in site.categories["IR in Pop Culture"] %}
  <div>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
