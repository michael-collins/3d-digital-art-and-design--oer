---
title: Lesson 01
subtitle: Introduction to 3D
layout: lesson
link: lesson-01
---

##Presentation
##Reading
##Exercise
{% assign exercise = site.exercises | where: exercise.url, "maya-image-planes-for-modeling" %}
   <h2><a href="{{ exercise.url | prepend: site.baseurl }}"><span class="exercise-title">{{ exercise.title }}</span>: <span class="exercise-subtitle">{{ exercise.subtitle }}</span></a></h2>
   <p>{{content}}</p>
{% endfor %}

{% include feedback.md %}
