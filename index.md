---
layout: default
title: ""
---

<h1>Home Page</h1>

Welcome :)

{% for post in site.posts %}
  <strong>{{ post.title }}</strong>
  <a href="https://pedrozanineli.github.io/truce.github.io{{ post.url }}">Link</a>
{% endfor %}
