---
layout:     post
title:      "Principio de Pareto"
subtitle:   "Céntrate en lo importante"
date:       2021-04-11 16:30:00
author:     "Aunitz Giménez"
header-img: "img/post-bg-70.jpg"
tags:       [leyes y principios de usabilidad]
---

<p>El <strong>principio de Pareto</strong> es también conocido como <strong>la regla del 80/20</strong>. La enunció por primera vez en 1896 el economista italiano Vilfredo Pareto.</p>

<p>Vilfredo Pareto descubrió que el 20% de los propietarios poseían el 80% de las tierras de Italia. Esta misma relación de 80/20 se ha aplicado con éxito en ámbitos tan dispares como la política, la economía, el control de calidad, el desarrollo de software o la seguridad de las redes informáticas.</p>

<p>La relación de 80/20 no es una distribución que haya que tomar de manera literal, ya que puede variar de un contexto a otro. Sin embargo, de manera aproximada, <strong>suele ser de aplicación para sistemas desequilibrados</strong>.</p>

<script src="//cdn.jsdelivr.net/npm/chart.js@3.1.0/dist/chart.min.js"></script>

<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>

<p><img src="{{ site.baseurl }}/img/principio-de-pareto.gif" alt="Diagrama de Pareto"></p>

<p>Algunos ejemplos clásicos:</p>
<ul>
    <li>El 80% de la productividad laboral proviene del 20% del tiempo de trabajo.</li>
    <li>El 80% de los errores son causados por el 20% del código fuente.</li>
    <li>El 80% de los ingresos procede del 20% de los clientes.</li>
</ul>

<h2>¿Cómo aplicamos el principio de Pareto en usabilidad?</h2>
<p>En usabilidad es habitual que <strong>la mayoría de las quejas de los usuarios (80%) proceda de unos pocos problemas de usabilidad (20%)</strong>. Es por ello por lo que nuestros esfuerzos deben centrarse en identificar y resolver estos pocos problemas y no dispersar nuestro trabajo en tratar de resolver “todos” los problemas de usabilidad.</p>

<p>Otra aplicación habitual del principio de Pareto en usabilidad se produce cuando <strong>la mayoría del tráfico (80%) de una web o aplicación se concentra en unos pocos contenidos (20%)</strong>. Cuanto esto ocurre, debemos concentrarnos en mejorar y actualizar estos pocos contenidos.</p>

<p>Un ejemplo adicional para tener en cuenta en usabilidad sería cuando <strong>la mayoría del tiempo de nuestros usuarios (80%) los pasan realizando unas pocas tareas (20%)</strong>.</p>

<p>En definitiva, lo que nos hace ver el principio de Pareto es que <strong>nuestros recursos son finitos y debemos destinarlos a lo que sea más importante para nuestros usuarios</strong>. Invirtiendo nuestro tiempo y esfuerzo en estas áreas clave maximizaremos el beneficio obtenido.</p>