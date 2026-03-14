---
layout: page
title: ChatGPT
permalink: /categories/chatgpt/
---

<ul>
  {% for post in site.categories.chatgpt %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>