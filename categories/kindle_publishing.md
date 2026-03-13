---
layout: page
title: Kindle Publishing
permalink: /categories/kindle_publishing/
---

<ul>
  {% for post in site.categories.kindle_publishing %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>