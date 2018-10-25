---
layout: default
title: 1.1 Основные определения
---

<ul>
  {% for page in site.pages %}
    {% if page.folder == 'cmb' %}
        <li>
          <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
        </li>
    {% endif %}
  {% endfor %}
</ul>