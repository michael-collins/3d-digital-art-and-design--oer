---
title: Lesson 01
subtitle: Introduction to 3D
layout: lesson
link: lesson-01
---

##Presentation
##Reading
##Exercise
<div class="exercises">
			{% for exercise in site.exercises %}
			   <h2><a href="{{ exercise.url | prepend: site.baseurl }}"><span class="exercise-title">{{ exercise.title }}</span>: <span class="exercise-subtitle">{{ exercise.subtitle }}</span></a></h2>
			   <p>{{content}}</p>
			{% endfor %}
		</div>
maya-image-planes-for-modeling

{% include feedback.md %}
