---
layout: page
permalink: /publications/
title: publications
description: An up-to-date list is available on <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a>.
years: [2021, 2020, 2019, 2018]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
