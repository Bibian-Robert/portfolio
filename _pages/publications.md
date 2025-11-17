---
layout: default
title: Publications
permalink: /publications/
---

<section class="section">
  <h2>Publications</h2>
  <ul>
  {% for pub in site.data.publications %}
    <li><strong>{{ pub.year }}</strong> — {{ pub.title }}. <em>{{ pub.journal }}</em>. <a href="{{ pub.url }}">View</a></li>
  {% endfor %}
  </ul>
</section>
