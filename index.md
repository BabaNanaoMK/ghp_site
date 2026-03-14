---
layout: default
title: Blog
---

# こんにちは、バナナ です

AIに関するよしなしごとを徒然なるままに記載します。

## カテゴリ

<ul class="category-list">
  <li><a href="{{ '/categories/claude/' | relative_url }}">Claude</a></li>
  <li><a href="{{ '/categories/codex_cli/' | relative_url }}">Codex CLI</a></li>
  <li><a href="{{ '/categories/gemini_cli/' | relative_url }}">Gemini CLI</a></li>
  <li><a href="{{ '/categories/antigravity/' | relative_url }}">Antigravity</a></li>
  <li><a href="{{ '/categories/gas/' | relative_url }}">GAS</a></li>
  <li><a href="{{ '/categories/github_pages/' | relative_url }}">GitHub Pages</a></li>
  <li><a href="{{ '/categories/jekyll/' | relative_url }}">Jekyll</a></li>
  <li><a href="{{ '/categories/kindle_publishing/' | relative_url }}">Kindle Publishing</a></li>
</ul>

## Blog
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">
      {{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}
    </a>
  </li>
{% endfor %}
</ul>
