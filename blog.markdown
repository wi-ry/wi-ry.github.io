---
layout: page
title: Blog
permalink: /blog

---

# Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      ### <a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
