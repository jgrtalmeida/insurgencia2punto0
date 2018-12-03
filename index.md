---
layout: default
title: "Insurgencia 2.0"
---
<div class="introduction">
  <h1>Hola.</h1>
<iframe width="560" height="315" src="https://www.youtube.com/embed/HKY3D5n0dCY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p align= "justify">Insurgencia 2.0 es una herramienta de producción de Memes para prácticas de narrativas digitales desde abajo. Su propósito es ser una herramienta para profesores colombianos en Cátedras de Paz. La parte técnica es basada en el tema <a href="https://jekyllrb.com/" target="_blank">Jekyll</a> <a href="http://elotroalex.github.io/ed/" target="_blank">Ed</a>. .
La historia del proyecto se puede verificar acá.
El concepto detrás consiste en entender que una de las dificultades del uso de narrativas digitales en contextos escolares es ignorar el ecosistema tecnológico en el cual la Generación que ambicionamos dialogar, que acá llamaremos <a href="https://www.youtube.com/watch?v=Jmbg50DtKSA" target="_blank">Generación #</a>, se mueve. Por eso la elección de reducir la producción narrativa a solamente un eje expresivo, en ese caso los Memes, ya que son un medio expresivo popular, juvenil e insurgente frente a los poderes y el statuo quo. Así mismo por su narrativa que se basa en el humor, la apropiación y transfiguración de discursos, pertenencia a la cultura juvenil pop, expresión de emociones simples y conexión con las prácticas cotidianas de los estudiantes.</p>
</div>

<hr>

<div class="toc">
  <h2>Índice</h2>
  <ul class="texts">
  {% for item in site.texts %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
