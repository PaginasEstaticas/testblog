---
layout: default
title: "Página Principal"
---

# Bienvenido a mi sitio
Aquí están mis entradas de blog, pepito:

{% for post in site.posts %}
**Título del post:** {{ post.title }}  
**URL del sitio:** {{ site.url }}  
**Base URL del sitio:** {{ site.baseurl }}  
**URL del post:** {{ post.url }}  
---
* [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
{% endfor %}