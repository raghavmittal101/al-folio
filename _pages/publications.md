---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
 <iframe width="480" height="270" src="https://www.youtube.com/embed/vZMkQBOknoU?autoplay=1&loop=1" frameborder="0" allowfullscreen></iframe>
</div>
