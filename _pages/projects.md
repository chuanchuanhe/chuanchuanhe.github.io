---
layout: page
permalink: /projects/
title: Projects
description:
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->
<!-- <div class="publications">

{% bibliography %}

</div> -->

<!-- <div class="project-grid"> -->
<div>
  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>