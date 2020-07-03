---
layout: default
title: home
permalink: /
---

[Part 1](/blog/_pages/1_1)

[Part 2](/blog/_pages/1_2)

{{ pages.url }}


<!-- Table of Contents -->
<ul>
    {% for pages in site.pages %}
      {% if pages.category == "pages" %}
        <li><a href="{{ pages.url }}">{{ pages.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

<ul>
    {% for pages in site.pages %}
      {% if pages.category == "alc" %}
        <li><a href="{{ pages.url }}">{{ pages.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>