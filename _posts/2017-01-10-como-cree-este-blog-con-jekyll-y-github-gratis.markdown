---
layout:     post
title:      "Cómo cree este blog con Jekyll y GitHub (gratis!)"
subtitle:   "Tutorial paso a paso"
date:       2017-01-10 09:30:00
author:     "Aunitz Giménez"
header-img: "img/post-bg-06.jpg"
---

<p>He pensado que en mi primer post podría explicar cómo cree este blog.</p>

<p>Mis <strong>requisitos</strong> de partida eran:</p>
<ul>
	<li>Que el mantenimiento no me llevase mucho tiempo.</li>
	<li>Que tuviese una estética minimalista y muy centrada en el contenido.</li>
	<li>Responsive Web Design. Es decir, adaptable al tamaño de la pantalla del dispositivo.</li>
	<li>Que tuviese un feed XML.</li>
	<li>Que los lectores pudiesen comentar mis posts.</li>
	<li>Un excelente rendimiento (velocidad de carga, especialmente).</li>
</ul>

<p>Buscando, buscando... me tope con los <strong>generadores de sitios web estáticos</strong> (<a href="https://www.staticgen.com/">static site generators</a>). Me encantó su filosofía.</p>

<p>Básicamente se trata de herramientas que permiten administrar los contenidos de un sitio web, de manera similar a un <a href="https://es.wikipedia.org/wiki/Sistema_de_gesti%C3%B3n_de_contenidos">CMS</a>, pero cuyo formato de salida es un sitio web completamente estático. Es decir, compuesto de páginas HTML, CSS y algo de JavaScript.</p>

<p>De los muchos generadores que existen me decanté por <a href="https://jekyllrb.com/">Jekyll</a>. El motivo principal fué que <a href="https://github.com/">GitHub</a> permite generar y alojar páginas con Jekyll de manera completamente gratuita. De ese modo, me ahorraba tener que montar la infraestructura del generador en local y me ahorraba también el dinero del hosting del blog.</p>

<h2 class="section-heading">Cómo lo hice</h2>

<p>Muy sencillo:</p>
<ol>
	<li>Seguí los pasos del excelente tutorial <a href="https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/">Build A Blog With Jekyll And GitHub Pages</a> publicado en Smashing Magazine.</li>
	<li>Realicé algunos pequeños cambios en el HTML de la plantilla utilizada para adecuarla un poco a mis preferencias y para traducir los literales que incluía al español.</li>
	<li>Si quieres alojar el blog de manera completamente gratuita, GitHub te proporciona un dominio del tipo <em>yourname.github.io</em>. Yo prefiría tener un dominio propio, así que compré aunitz.net y configuré el CNAME DNS para que apuntase a aunitz.github.io. Cómo hacerlo también se explica en el tutorial de Smashing Magazine.</li>
</ol>

<p><iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/cmYOcuaDcZY?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen>
	<p>Your browser does not support iframes.</p>
</iframe></p>