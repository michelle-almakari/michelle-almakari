---
layout: page
permalink: /publications/
title: Publications
longtitle: Publications
description: Peer-reviewed publications by categories in reversed chronological order. 
years: [2020, 2019, 2017]
years_conf: [2016]
nav: true
---
_Last Updated May 2021_ 

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


<br/><br/>
## Conference Papers 

<div class="publications">

{% for y in page.years_conf %}
<h2 class="year">{{y}}</h2>
{% bibliography -f conference_papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
