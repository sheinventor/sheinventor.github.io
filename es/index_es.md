---
layout: default_es  
title: "Blog en español"
lang: "es"
permalink: /es/
---

<div class="posts">
  {% for post in site.posts limit:5 %}
    {% if post.lang == page.lang %}
      <article class="post">
        <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
        <div class="entry">
          {{ post.excerpt }}
        </div>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leer más</a>
      </article>
    {% endif %}
  {% endfor %}
</div> 

Este es el indice en español

No era ciencia, era magia. 

images/Emanuel-2.png

Magia que hoy llevo conmigo. (En los cursos de ciencia que doy a niñas y niños)

![Persona enseñando ciencia a niños]({{ site.baseurl }}/images/Emanuel-4.png)
