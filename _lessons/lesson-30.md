---
title: Lesson 30
subtitle: Lesson 30 Topic
layout: lesson
date: 4/29/2016
topics: maya-animation
---

###Topics
<ul>
 {% for topic in site.topics %}
   {% for tag in topic.tags %}
       {% if tag == "{{site.lessons.topics}}" %}
           <li><a href="{{ topic.permalink | prepend: site.baseurl }}">{{topic.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>

###Exercise