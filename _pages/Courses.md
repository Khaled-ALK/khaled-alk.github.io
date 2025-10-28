---
layout: page
title: courses
permalink: /courses/
nav: true
nav_order: 4   # change this number to move it left/right in the navbar
---

<!--
This page shows your courses as cards grouped by category.
Each "course" is a markdown file in _projects/ with front-matter including:
  title: ...
  category: Math | COS | Etc
  img: /assets/courses/<slug>/thumb.jpg
  permalink: /courses/<slug>/
  importance: 1   (smaller number = earlier in the grid)
-->

{% assign groups = "Math|COS|Etc" | split: "|" %}

{% for group in groups %}
## {{ group }}
<div class="projects-grid">
  {% assign items = site.projects | where: "category", group | sort: "importance" %}
  {% if items.size == 0 %}
  <p><em>No courses yet in {{ group }}.</em></p>
  {% endif %}
  {% for course in items %}
    <a class="project-card" href="{{ course.url | relative_url }}">
      {% if course.img %}
      <img src="{{ course.img | relative_url }}" alt="{{ course.title }}" />
      {% endif %}
      <div class="project-card-title">{{ course.title }}</div>
    </a>
  {% endfor %}
</div>
{% endfor %}

<style>
/* Simple grid using theme defaults */
.projects-grid { display:grid; grid-template-columns: repeat(auto-fill,minmax(220px,1fr)); gap: 16px; margin: 16px 0 32px; }
.project-card { display:block; border:1px solid var(--global-border-color,#e5e5e5); border-radius:12px; overflow:hidden; text-decoration:none; }
.project-card img { width:100%; height:150px; object-fit:cover; display:block; }
.project-card-title { padding:10px 12px; font-weight:600; color:inherit; }
.project-card:hover { box-shadow: 0 6px 18px rgba(0,0,0,0.08); transform: translateY(-2px); transition: all .15s ease; }
</style>
