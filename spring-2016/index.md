---
layout: default
title: Spring 2016
subtitle: Section 1
---
<div class="spring-2016">
    {% for lesson in site.lessons %}
       <h4><a href="{{ lesson.url | prepend: site.baseurl }}"><span class="lesson-title">{{ lesson.title }}</span>: <span class="lesson-subtitle">{{ lesson.subtitle }}</span></a></h4>
       <p>{{content}}</p>
    {% endfor %}
</div>
