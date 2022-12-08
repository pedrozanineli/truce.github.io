---
layout: default
---

## Página Inicial

Bem vinda(o)!

Teste

{% for dado in site.data.dados %}
  <div style="margin-bottom:8px;border: 0.5px solid grey;border-radius: 5px;">
    <div style="padding:10px;">
      {{ dado.name }},{{ dado.date }}
    </div>
  </div>
{% endfor %}
