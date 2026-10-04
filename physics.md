---
layout: default
title: Physics
---

<h1>Physics</h1>
<ul>
  {% for post in site.physics %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>