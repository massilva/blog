---
layout: post
title:  "Curso front-end"
date:   2018-02-03 08:00:00
categories: Cursos
---

Sexta dia *02/02/2018*, o Victor Romário e Eu, realizamos a última aula da primeira turma do ***Curso de Desenvolvimento Web - Front End***.

Neste curso os alunos aprenderam *HTML5*, *CSS3* e *Javascript*. Utilizamos dois dos frameworks mais utilizados no mercado de trabalho, o *bootstrap* e o *jQuery*.

Os alunos progrediram muito bem, vejam:

<ul>
{% assign pages = (site.data.pages | sort: 'name') %}
{% for page in pages %}
  <li>
    <a href="{{ page.github }}">{{ page.name }}</a>
  </li>
{% endfor %}
</ul>
