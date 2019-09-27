---
layout: page
show_meta: false
title: "Eventi"
subheadline: "Calendario degli incontri programmati"
header:
   title:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/eventi/"
---

### Calendario degli eventi al Laboratorio Aperto di rimini

Il Laboratorio Aperto di Rimini è lo spazio che accoglierà anche quest'anno le attività del Coderdojo di Rimini. Via Dei Cavalieri 22, Rimini (RN)

<iframe src="https://calendar.google.com/calendar/embed?src=laboratorioapertoriminitiberio%40gmail.com&ctz=Europe%2FRome" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

### Il luogo

Il Laboratorio Aperto Rimini Tiberio è in centro a Rimini vicino al Ponte di Tiberio, consigliamo il parcheggio, se venite in automobile, presso il parcheggio Tiberio:

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2866.959361511206!2d12.564301251683695!3d44.06354777900686!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x132cc336cd47bf51%3A0xe581edc948251a2e!2sLaboratorio+Aperto+Rimini+Tiberio!5e0!3m2!1sen!2sit!4v1537536736653" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Eventi pubblicati su [Zen CoderDojo](https://zen.coderdojo.com/dojos/it/rimini-province-of-rimini/rimini "Evento CoderDojoRimini")


<ul>
  {% for post in site.categories.eventi %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
