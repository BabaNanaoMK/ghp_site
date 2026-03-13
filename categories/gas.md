---
layout: page
title: GAS
permalink: /categories/gas/
---

<ul>
  {% for post in site.categories.gas %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>