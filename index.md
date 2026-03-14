---
layout: home
title: Blog
---

# こんにちは、バナナ です

AIに関するよしなしごとを徒然なるままに記載します。

## カテゴリ

- [Claude]({{ '/categories/claude/' | relative_url }})
- [Codex_CLI]({{ '/categories/codex_cli/' | relative_url }})
- [Gemini_CLI]({{ '/categories/gemini_cli/' | relative_url }})
- [Antigravity]({{ '/categories/antigravity/' | relative_url }})
- [GAS]({{ '/categories/gas/' | relative_url }})
- [GitHub_Pages]({{ '/categories/github_pages/' | relative_url }})
- [Jekyll]({{ '/categories/jekyll/' | relative_url }})
- [Kindle_Publishing]({{ '/categories/kindle-publishing/' | relative_url }})

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
