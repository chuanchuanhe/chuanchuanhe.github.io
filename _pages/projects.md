---
layout: page
permalink: /projects/
title: Projects
description:
nav: true
nav_order: 4
---
<div class="projects">
   <div class="grid" style="position: relative; height: 422.667px;">
      {% assign sorted_projects = site.projects | sort: "importance" %}
      {% for project in sorted_projects %}
         {% include projects.liquid %}
      {% endfor %}
   </div>
</div>
