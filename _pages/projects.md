---
layout: default
title: Projects
permalink: /projects/
---

<section class="section">
  <h2>Selected Projects</h2>

  {% for p in site.data.projects %}
  <article class="card">
    <h3>{{ p.name }}</h3>
    <p>{{ p.description }}</p>
    <p><a href="{{ p.url }}">Read more</a></p>
  </article>
  {% endfor %}
</section>
