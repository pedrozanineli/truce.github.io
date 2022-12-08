---
layout: default
---

<h1>Página Inicial</h1>

Bem vinda(o)!

Os posts disponíveis são os seguintes:

{% for post in site.posts %}
  <strong>{{ post.title }}</strong>
  <a href="https://pedrozanineli.github.io/truce.github.io{{ post.url }}">Link para o post</a>
{% endfor %}
