---
title: postindex
author: Rami Hovi
created: 2025-04-18 17:28
tags: [ index, posts ]
---

# postindex

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
