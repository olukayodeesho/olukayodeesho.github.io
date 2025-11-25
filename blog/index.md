---
layout: page
title: "Blog"
---

# Blog

Welcome to my engineering blog.

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
