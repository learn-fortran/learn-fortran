---
layout: page
title: Lessons
permalink: /lessons/
---

<ol>
{% for lecture in site.lectures %}
  {% if lecture.published %}
    <li><a href="{{ lecture.url }}">{{ lecture.title }}</a></li>
  {% endif %}
{% endfor %}
</ol>
