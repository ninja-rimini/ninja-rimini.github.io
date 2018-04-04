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

<iframe src="https://calendar.google.com/calendar/b/4/embed?showTitle=0&amp;showCalendars=0&amp;showTz=0&amp;mode=WEEK&amp;height=600&amp;wkst=2&amp;hl=it&amp;bgcolor=%23FFFFFF&amp;src=coderdojorimini%40gmail.com&amp;color=%23711616&amp;ctz=Europe%2FRome" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

Eventi pubblicati su [Zen CoderDojo](https://zen.coderdojo.com/dojos/it/rimini-province-of-rimini/rimini "Evento CoderDojoRimini")


<ul>
  {% for post in site.categories.eventi %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
