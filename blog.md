---
layout: page
title: Blog
background: grey
---

# Blog posts

<ul style="margin-top:2rem;">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      |
      {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
