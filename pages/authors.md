---
layout: single
title: Authors
permalink: /authors/
---

<ul>
{% for member in site.data.authors %}
{% assign author = member[1] %}
  <li>
    <p>{{ author.name }}</p>
  </li>
{% endfor %}
</ul>