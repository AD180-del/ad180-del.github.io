---
layout: default
permalink: /irinpopculture/
title: "IR in Pop Culture"
---

Welcome to "IR in Pop Culture". This series of short articles aims to explain concepts from IR with the help of pop culture.

<h2>Articles</h2>

<ul class="post-list">
  {% assign posts = site.categories["IR in Pop Culture"] | sort: "date" | reverse %}
  {% for post in posts %}
    <li class="post-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p class="post-excerpt">{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
