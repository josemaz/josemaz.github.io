---
layout: default
title: Blog
---

Bienvenidos al blog !!

<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%d-%b-%Y" }} | {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>