---
layout: default
title: Talks & Presentations
permalink: /talks/
---

<section class="section">
  <h2>Talks & Presentations</h2>
  <ul>
  {% for t in site.data.talks %}
    <li><strong>{{ t.date }}</strong> — {{ t.title }} ({{ t.venue }})</li>
  {% endfor %}
  </ul>
</section>
