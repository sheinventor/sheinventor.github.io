---
layout: default_fr  # Usa el layout correspondiente en francés
title: "Blog en Français"
lang: "fr"
permalink: /fr/
---

<div class="posts">
  {% for post in site.posts limit:5 %}
    {% if post.lang == page.lang %}
      <article class="post">
        <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
        <div class="entry">
          {{ post.excerpt }}
        </div>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Lire la suite</a>
      </article>
    {% endif %}
  {% endfor %}
</div> 

## ¡Bienvenido a mi nuevo cómic!

Este es el primer cómic en español. Aquí puedes hablar sobre el contenido del cómic, los temas o algún contexto divertido.