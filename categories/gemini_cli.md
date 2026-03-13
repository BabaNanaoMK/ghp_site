---
layout: page
title: GeminiCLI
permalink: /categories/gemini_cli/
---

<ul>
  {% for post in site.categories.gemini_cli %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>