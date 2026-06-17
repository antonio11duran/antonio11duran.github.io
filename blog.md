---
layout: page
title: Blog
permalink: /blog/
---

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #888; font-size: 0.9em;"> — {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
