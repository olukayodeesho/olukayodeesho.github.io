---
layout: page
title: "Blog"
---

Welcome to my engineering blog.

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    {% if post.date %}
      — <small>{{ post.date | date: "%B %d, %Y" }}</small>
    {% endif %}
  </li>
{% endfor %}
</ul>
