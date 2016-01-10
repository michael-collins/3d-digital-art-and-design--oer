---
title: Lesson 11
subtitle: Fabrication
layout: lesson
date: 2/16/2016
---

###Topics
<ul>
 {% for topic in site.topics %}
   {% for tag in topic.tags %}
       {% if tag == "maya-fabrication" %}
           <li><a href="{{ topic.url | prepend: site.baseurl }}">{{topic.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>