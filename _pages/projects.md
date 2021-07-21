---
layout: page
permalink: /projects/
title: Projects
nav: true
categories:
  - system
  - learning
dict:
  system: Distributed System
  learning: Machine Learning
---


Ours not to do and die, ours but to reason why.

<div class="projects">
  {% for category in page.categories %}
  <div class="category">
  <h2>{{ page.dict[category] }}</h2>
  {% assign projects = site.projects | where: "category", category | sort: "importance" %}
  {% for project in projects %}
    <div class="project">
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    </div>
  {% endfor%}
  </div>
  {% endfor%}

</div>
