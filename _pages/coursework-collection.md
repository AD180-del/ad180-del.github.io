---
layout: default
permalink: /coursework-collection/
title: "Coursework Collection"
---
Welcome to "Coursework Collection". This is an archive of papers and assignments written for university coursework.

<h2>Articles</h2>

<ul class="post-list">
  {% assign posts = site.categories["Coursework Collection"] | sort: "date" | reverse %}
  {% for post in posts %}
    <li class="post-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p class="post-excerpt">{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
