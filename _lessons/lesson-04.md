---
title: Lesson 04
subtitle: Camera
layout: lesson
date: 1/21/2016
---

###Topics
<ul>
 {% for topic in site.topics %}
   {% for tag in topic.tags %}
       {% if tag == "maya-camera" %}
           <li><a href="{{ topic.url | prepend: site.baseurl }}">{{topic.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>
