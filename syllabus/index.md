---
title: 3D Digital Art and Design OER
subtitle: Syllabus
layout: default
---

<div class="syllabus">
    {% for syllabus in site.syllabus %}
       <h2><a href="{{ syllabus.url | prepend: site.baseurl }}"><span class="syllabus-title">{{ syllabus.title }}</span>: <span class="syllabus-subtitle">{{ syllabus.subtitle }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
