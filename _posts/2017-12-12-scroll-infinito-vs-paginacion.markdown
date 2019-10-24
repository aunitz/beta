---
layout:     post
title:      "Scroll infinito vs paginación"
subtitle:   "Cuándo utilizar uno u otro"
date:       2017-12-12 10:00:00
author:     "Aunitz Giménez"
header-img: "img/post-bg-14.jpg"
tags:       [buenas prácticas de usabilidad]
---

<p>Desde el punto de vista de la usabilidad, una y otra t&eacute;cnica tiene sus pros y sus contras.</p>

<p>Las conclusiones a las que he llegado son las siguientes.</p>

<h2>Scroll infinito</h2>

<p>Se utiliza especialmente en webs en las que el usuario no est&aacute; buscando algo concreto. Webs en las que se pretende que el usuario descubra contenido.</p>

<p>Por ejemplo, el feed de contenidos de muchas redes sociales: Facebook, Pinterest, Twitter...</p>

<p>Hacer scroll es m&aacute;s c&oacute;modo que hacer clic y el usuario se sumerge en un scroll infinito de contenidos.</p>

<p>Inconvenientes:</p>
<ul>
    <li>El rendimiento es peor que con la paginaci&oacute;n. Por dos motivos: hay un delay en la carga de contenidos y la p&aacute;gina va ocupando cada vez m&aacute;s memoria.</li>
    <li>Se dificulta el localizar una fila concreta, ya que la referencia de la barra de scroll del navegador pierde su utilidad al estar recalcul&aacute;ndose.</li>
    <li>Tras entrar a editar un contenido y volver a la p&aacute;gina de listado puede que el usuario ya no localice, ni tenga a la vista, el &iacute;tem que acaba de editar.</li>
</ul>

<h2>Paginaci&oacute;n</h2>

<p>Se utiliza t&iacute;picamente en webs que muestran los resultados de una b&uacute;squeda. Por ejemplo, Google. El usuario espera encontrar el contenido que busca en la primera p&aacute;gina y si no es as&iacute;, avanza a trav&eacute;s de la paginaci&oacute;n. Pero en realidad, el usuario no quiere usar la paginaci&oacute;n. Lo que quiere es que la primera pantalla le muestre la soluci&oacute;n.</p>
<p>Otras ventajas son que:</p>

<ul>
    <li>Aporta mayor sensaci&oacute;n de control al usuario que el scroll infinito.</li>
    <li>Facilita el volver a una fila concreta ya que estar&aacute; en "la misma posici&oacute;n" en la que estaba la primera vez que la vimos.</li>
    <li>As&iacute; como volver a una misma posici&oacute;n de la paginaci&oacute;n tras entrar a editar un contenido.</li>
</ul>

<p>El principal inconveniente de la paginaci&oacute;n es que requiere de una acci&oacute;n por parte del usuario m&aacute;s inc&oacute;moda que la del scroll. Es decir, es m&aacute;s "molesto" hacer clic que usar la rueda del rat&oacute;n.</p>

<h2>Conclusi&oacute;n</h2>

<p><strong>Cada caso es distinto</strong> y para tomar una decisi&oacute;n final hay que ver el uso que hacen los usuarios de las tablas de resultados en cada aplicaci&oacute;n.</p>

<p>Como pauta general, vemos que el <strong>scroll infinito</strong> es la mejor opci&oacute;n para aplicaciones en las que el usuario no busca algo en concreto y lo que quiere es <strong>descubrir contenido nuevo</strong> (Twitter, Facebook), as&iacute; como webs de contenido visual (Pinterest, Instagram).</p>

<p>La <strong>paginaci&oacute;n</strong> es una opci&oacute;n est&aacute;ndar y m&aacute;s adecuada para aplicaciones orientadas a <strong>localizar un contenido concreto</strong> y ejecutar una tarea con el mismo.</p>

<p>Finalmente, aconsejamos que si los <strong>listados no son excesivamente largos</strong> (100-150 filas) se muestren todos los resultados en pantalla desde el primer momento, <strong>sin paginaci&oacute;n y sin scroll infinito</strong>.</p>