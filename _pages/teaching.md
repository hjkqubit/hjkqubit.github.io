---
layout: page
permalink: /teaching/
title: teaching
description: Teaching Assistantships
years: [2020,2019]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f teachings -q @*[year={{y}}]* %}
{% endfor %}

</div>
