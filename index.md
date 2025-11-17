---
layout: default
title: Home
permalink: /
---

<section class="section">
  <h1>Hi, I'm Bibian N. Robert</h1>
  <p class="muted">Geospatial Research Scientist • Data & Spatial Analytics • Capacity Building</p>
</section>

<section class="section card">
  <h2>Highlights</h2>
  <ul class="project-list">
    {% for p in site.data.projects %}
      <li><a href="{{ p.url }}">{{ p.name }}</a> — {{ p.short }}</li>
    {% endfor %}
  </ul>
</section>
