---
layout: page
title: Jekyll
permalink: /categories/jekyll/
---

<ul>
  {% for post in site.categories.jekyll %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>