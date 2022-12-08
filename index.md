---
layout: default
---

<h2>Página Inicial</h2>

Bem vinda(o)!

{% for post in site.posts %}
  <strong><h4>{{ post.title }}</h3></strong>
  <p>{{post.url}}</p>
  <a href="{{ post.url }}">Link para o post</a>
{% endfor %}
