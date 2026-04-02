---
layout: default
title: Blog
---

# My Blog 

Here are my blog posts:

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <small>({{ post.date | date: "%B %d
