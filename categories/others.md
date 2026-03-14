---
layout: page
title: その他
permalink: /categories/others/
---

<ul>
  {% for post in site.categories.others %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>