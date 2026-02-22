---
layout: default
title: Blog
---

# こんにちは、バナナ です

AI習得の良しな仕事を徒然なるままに記載します。

# Blog
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">
      {{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}
    </a>
  </li>
{% endfor %}
</ul>
