---
layout: page
permalink: /publications-by-year/
title: publications by year
description: publications in reversed chronological order.
years: [2024, 2023, 2022, 2021, 2020, 2018, 2017, 2016]
---

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
