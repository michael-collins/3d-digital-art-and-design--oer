---
layout: default
title: Exercise 1
category: test
comments: true
---

{% for exercise in site.exercises %}
{% for exercise in exercises.title %}
{% if title == "maya-image-planes-for-modeling" %}
<a href="{{ exercise.url | prepend: site.baseurl }}">{{exercise.title}}</a>
{% endif %}
{% endfor %}
{% endfor %}

##[Exercise 1 Dropbox](dropbox.psu.edu)
