---
layout: default
title: 3D Digital Art and Design OER
offering: Spring 2016
section: 001
---
<h2>{{page.offering}}</h2>
<h3>Section: {{page.section}}</h3>

<div class="spring-2016">
    {% for lesson in site.lessons %}
       <h4>{{ lesson.date }}</h4>
       <h5><a href="{{ lesson.url | prepend: site.baseurl }}"><span class="lesson-title">{{ lesson.title }}</span>: <span class="lesson-subtitle">{{ lesson.subtitle }}</span></a></h5>
       <p>{{content}}</p>
    {% endfor %}
</div>
