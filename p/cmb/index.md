---
layout: default
title: сомбианторные алгоритмы
---

# {{ page.title }}

<ul>
  {% for page in site.pages %}
    {% if page.folder == 'cmb' %}
        <li>
          <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
        </li>
    {% endif %}
  {% endfor %}
</ul>