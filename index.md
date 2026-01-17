---
layout: default
title: Home
---

## Welcome to DataGeeks 
{{ site.description }}

---

### Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>
      <small> — {{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>
