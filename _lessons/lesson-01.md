---
title: Lesson 01
subtitle: Introduction to 3D
layout: lesson
link: lesson-01
---

##Presentation
##Reading
##Exercise


{% for exercise in site.exercises %}
   {% if exercise.link == "maya-image-planes-for-modeling" %}
      <h2><a href="{{ exercise.url | prepend: site.baseurl }}"><span class="exercise-title">{{ exercise.title }}</span>: <span class="exercise-subtitle">{{ exercise.subtitle }}</span></a></h2>
      <p>{{content}}</p>
   {% endif %}
{% endfor %}

{% include feedback.md %}
