---
layout: page
title: CodexCLI
permalink: /categories/CodexCLI/
---

<ul>
  {% for post in site.categories.codexcli %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>