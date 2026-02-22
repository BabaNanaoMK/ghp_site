---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Blog
---
# こんにちは、Masato です

AI習得の良しな仕事を徒然なるままに記載します。

# Blog

<ul>
{% for post in paginator.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}</a>
  </li>
{% endfor %}
</ul>

{% if paginator.total_pages > 1 %}
  <nav>
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path | relative_url }}">← Newer</a>
    {% endif %}
    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path | relative_url }}">Older →</a>
    {% endif %}
  </nav>
{% endif %}