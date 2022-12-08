---
layout: default
---

<h2>Página Inicial</h2>

Bem vinda(o)!

{% link http://pedrozanineli.github.io//my-post %}

{% for post in site.posts %}
  <strong>{{ post.title }}</strong>
  <p>{{post.url}}</p>
  <a href="https://pedrozanineli.github.io/truce.github.io{{ post.url }}">Link para o post</a>
{% endfor %}
