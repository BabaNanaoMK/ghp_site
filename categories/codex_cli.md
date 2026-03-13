---
layout: page
title: CodexCLI
permalink: /categories/codex_cli/
---

<ul>
  {% for post in site.categories.codex_cli %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>