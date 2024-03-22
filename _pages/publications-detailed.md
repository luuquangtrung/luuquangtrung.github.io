---
layout: page
permalink: /publications-detailed/
title: publications
description: publications in reversed chronological order.
years: [2023, 2022, 2021, 2020, 2018, 2017, 2016]
---
<!-- _pages/publications.md -->
<div class="publications">
  

For more updated list of publications, please visit my <a href="https://www.researchgate.net/profile/Quang_Trung_Luu">ResearchGate</a>, <a href="https://scholar.google.fr/citations?user=GqQcLAIAAAAJ&hl=fr">Google Scholar</a>, or <a href="https://cv.archives-ouvertes.fr/quang-trung-luu">HAL Archives Ouvertes</a>.
  
A list of publications by categories is also maintained <a href="https://luuquangtrung.github.io/publications-by-categories/">here</a>.

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
