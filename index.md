---
layout: default
title: "ホーム"
---

## ようこそ、My Blogへ！

最新の記事をお楽しみください。

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
