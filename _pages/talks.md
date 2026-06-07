---
layout: page
permalink: /talks/
title: Talks
description:
types: [Invited talks, Seminars, Contributed talks, Poster]
nav: true
nav_order: 3
---
<!-- _pages/talks.md -->
<div class="publications">

{%- for y in page.types %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[type={{y}}]* %}
{% endfor %}

</div>
