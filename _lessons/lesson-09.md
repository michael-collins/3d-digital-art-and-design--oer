---
title: Lesson 09
subtitle: scripting
layout: lesson
date: 2/9/2016
---

###Topics
<ul>
 {% for topic in site.topics %}
   {% for tag in topic.tags %}
       {% if tag == "maya-scripting" %}
           <li><a href="{{ topic.url | prepend: site.baseurl }}">{{topic.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>
