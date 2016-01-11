---
layout: default
title: Exercise 1
category: test
comments: true
---

{% for exercise in site.exercises %}
{% for tag in exercises.tags %}
{% if tag == "maya-image-planes-for-modeling" %}
<a href="{{ exercise.url | prepend: site.baseurl }}">{{exercise.title}}</a>
{% endif %}
{% endfor %}
{% endfor %}

##[Exercise 1 Dropbox](dropbox.psu.edu)
