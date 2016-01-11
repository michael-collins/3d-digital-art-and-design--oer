---
title: Syllabus
subtitle: Semester Listing
layout: default
---
<h2>Semester</h2>
[Spring 2016]({{ site.baseurl }}/spring-2016)

<div class="syllabus">
    {% for syllabus in site.syllabus %}
       <h2><a href="{{ syllabus.url | prepend: site.baseurl }}"><span class="syllabus-title">{{ syllabus.course-abbrv }}{{ syllabus.course-number }}</span>: <span class="syllabus-subtitle">{{ syllabus.course-title }} - {{ syllabus.semester }}{{ syllabus.year }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
