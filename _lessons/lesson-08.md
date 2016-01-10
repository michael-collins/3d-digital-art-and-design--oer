---
title: Lesson 08
subtitle: Compositing
layout: lesson
date: 2/4/2016
---

###Topics
<ul>
 {% for topic in site.topics %}
   {% for tag in topic.tags %}
       {% if tag == "maya-compositing" %}
           <li><a href="{{ topic.url | prepend: site.baseurl }}">{{topic.title}}</a></li>
        {% endif %}
   {% endfor %}
 {% endfor %}
</ul>

###Exercise

####<a href="/3d-digital-art-and-design--oer/exercises/maya-image-planes-for-modeling/maya-image-planes-for-modeling.html"><span class="exercise-title"> Maya Image Planes for Modeling</span></a>

        - exercise : maya-render-passes-in-mentalray