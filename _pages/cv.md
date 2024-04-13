---
layout: single
title: "My CV"
permalink: /cv/
hide_title: true # theuma: hide_title added to remove title from single.html layout
---

{% for i in (0..2) %}
![My CV Page {{ i }}](/assets/cv/cv-{{ i }}.png)
{% endfor %}