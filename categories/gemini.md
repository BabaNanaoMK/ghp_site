---
layout: page
title: Gemini
permalink: /categories/gemini/
---

<ul>
  {% for post in site.categories.gemini %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>