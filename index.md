---
layout: default
title: "Página Principal"
---

# Bienvenido a mi sitio
Aquí están mis entradas de blog:

{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}