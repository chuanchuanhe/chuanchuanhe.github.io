---
layout: page
permalink: /talks/
title: Talks
description: tdb
types: [Invited talks, Seminars, Contributed talks, Poster]
nav: true
nav_order: 3
---
<!-- _pages/talks.md -->
<div class="publications">

{%- for type in page.types %}

<h2 class="bibliography">{{ type }}</h2>

{% bibliography -f talks -q @*[type={{ type }}]* --group_by none %}

{% endfor %}

</div>
