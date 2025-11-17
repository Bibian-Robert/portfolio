---
layout: default
title: Capacity Building
permalink: /capacity-building/
---

<section class="section">
  <h2>Capacity Building & Training</h2>

  {% for c in site.data.capacity %}
  <article class="card">
    <h3>{{ c.title }}</h3>
    <p>{{ c.description }}</p>
  </article>
  {% endfor %}
</section>
