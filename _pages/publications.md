---
layout: page
permalink: /publications/
title: publications
description: Publications are also listed on <a href='https://scholar.google.co.nz/citations?user=OVBqXFEAAAAJ&hl=en'>Google Scholar</a>.
years: [2021, 2020, 2018, 2015, 2014]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
