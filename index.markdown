---
title: Home
date: 2020-08-09 17:35:00 Z
---


  {% for post in site.posts %}
    <h1>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h1>

  {% endfor %}
