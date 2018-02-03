---
layout: post
title:  "Curso front-end"
date:   2018-02-03 08:00:00
categories: Cursos
excerpt: Neste curso aprendemos a criar um site desde a sua prototipação até a sua publicação no site do github. Os alunos aprenderam HTML5, CSS3 e Javascript, começando do zero, através de aulas expositivas e muitas atividades práticas.
---

Em 2016, fizemos a primeira versão deste curso, juntamente com [Gláuber Brennon](https://github.com/gbrennon).

> A nossa missão com esse curso é qualificar as pessoas com as principais tecnologias utilizadas no mercado para que assim a área de computação, de modo geral, possa ter o seu valor reconhecido tanto pelas empresas quantos pelos próprios profissionais da área.

Sexta dia *02/02/2018* (em Salvador é dia de [Yemanjá](https://www.calendarr.com/brasil/dia-de-iemanja/)), o Victor Romário e Eu, realizamos a última aula da primeira turma do ***Curso de Desenvolvimento Web - Front End*** de 2018.

Neste curso aprendemos a criar um site desde a sua prototipação até a sua publicação no site do [Github](https://github.com/). Os alunos aprenderam como utilizar o *HTML5*, *CSS3* e *Javascript*, em conjunto com dois dos frameworks mais utilizados no mercado de trabalho, o *bootstrap* e o *jQuery*, para criar o seu site pessoal.

Apresentamos o conceito do [Mobile First](https://tableless.com.br/mobile-first-a-arte-de-pensar-com-foco/) e a importância de se utilizar o controle de versão no desenvolvimento de um projeto. Para isso, utilizamos o [GIT](https://git-scm.com/), onde os alunos aprenderam a atualizar o site utilizando o [Git bash](https://git-scm.com/downloads)(versão Terminal) e [Git GUI](https://git-scm.com/download/gui/windows)(versão Gráfica).

Eu fiquei muito feliz em vê o progresso dos alunos. A turma era heterogênea tinha pessoas que não eram da área, mais queriam aprender a criar o seu site, e pessoas que são estudantes, de algum curso da área, e estavam em busca de aprimorar os seus conhecimentos. E por isso, alguns alunos colocaram em prática o conhecimento adquirido em seu projeto pessoal enquanto outros seguiram a nossa idea de projeto, o ***[Currículo Online](https://vrpazdejesus.github.io/curso-dev-web)***.

![Turma 1]({{site.baseurl}}/assets/images/post/2018-02-03-curso-desenvolvimento-web-turma.jpg)

Ao final do curso os alunos tinham uma página de ***[Currículo Online](https://vrpazdejesus.github.io/curso-dev-web)*** [responsiva](https://en.wikipedia.org/wiki/Responsive_web_design), ou seja, se adapta às diferentes telas de dispositivos da forma que havíamos prototipados.  

![Currículo Online]({{site.baseurl}}/assets/images/post/2018-02-03-curso-desenvolvimento-web-final.png)

**Obrigado à todos os alunos pela confiança e pela participação em nosso curso.**

Abaixo está a lista com os resultados:

<ul>
{% assign pages = site.data.pages | sort: 'name' %}
{% for page in pages %}
  <li>
    <a href="{{ page.github }}">{{ page.name }}</a>
  </li>
{% endfor %}
</ul>
