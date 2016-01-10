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
       {% if tag == "maya-animation" %}
           <li><a href="{{ topic.permalink | prepend: site.baseurl }}">{{page.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>

###Exercise

####<a href="/3d-digital-art-and-design--oer/exercises/maya-image-planes-for-modeling/maya-image-planes-for-modeling.html"><span class="exercise-title"> Maya Image Planes for Modeling</span></a>