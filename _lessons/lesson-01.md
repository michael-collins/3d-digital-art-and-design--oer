---
title: Lesson 01
subtitle: Introduction to 3D
layout: lesson
link: lesson-01
---

##Presentation
##Reading
##Exercise

 {% for exercise in site.exercises | markdownify %}
     {% if exercise.link == "maya-image-planes-for-modeling" | markdownify %}
      <h2><a href="{{ site.baseurl }}{{ exercise.url }}"><span class="exercise-title"> {{ exercise.title }}</span>: <span class="exercise-subtitle"> {{ exercise.subtitle }}</span></a></h2>
      {{ exercise.content | markdownify }}
     {% endif %}
  {% endfor %}
