---
layout: default
title: Chemistry
---

<h1>Chemistry</h1>
<ul>
  {% for post in site.chemistry %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>