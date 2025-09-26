---
layout: home
title: Home
---

# Welcome to my blog

This is my personal where I post about my tech topics.

Below are my posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="date">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
