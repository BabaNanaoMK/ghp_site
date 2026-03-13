---
layout: page
title: GitHub Pages
permalink: /categories/github_pages/
---

<ul>
  {% for post in site.categories.github_pages %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>