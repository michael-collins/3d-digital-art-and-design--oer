---
layout: default
title: 3D Digital Art and Design OER
offering: Spring 2016
section: 001
---
<h2>{{page.offering}}</h2>
<h3>Section: {{page.section}}</h3>

####Week 1
#####1/12/2015
Lesson 1: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-01.html)

#####1/14/2015
Lesson 2: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-02.html)

####Week 2
#####1/19/2015
Lesson 3: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-03.html)

#####1/21/2015
Lesson 4: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-04.html)

####Week 3
#####1/26/2015
Lesson 5: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-05.html)

#####1/28/2015
Lesson 6: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-06.html)

####Week 4
#####2/2/2015
Lesson 7: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-07.html)

#####1/28/2015
Lesson 8: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-08.html)

####Week 5
#####2/9/2015
Lesson 9: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-09.html)

#####2/11/2015
Lesson 10: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-10.html)

####Week 6
#####2/16/2015
Lesson 11: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-11.html)

#####2/18/2015
Lesson 12: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-12.html)

####Week 7
#####2/23/2015
Lesson 13: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-13.html)

#####2/25/2015
Lesson 14: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-14.html)

####Week 8
#####3/2/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-15.html)

#####3/4/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-16.html)

####Spring Break
#####3/9/2015

#####3/11/2015

####Week 9
#####3/16/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-17.html)

#####3/18/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-18.html)

####Week 10
#####3/23/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-19.html)

#####3/25/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-20.html)

####Week 11
#####3/30/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-21.html)

#####4/1/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-22.html)

####Week 12
#####4/6/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-23.html)

#####4/8/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-24.html)

####Week 13
#####4/13/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-25.html)

#####4/15/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-26.html)

####Week 14
#####4/20/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-27.html)

#####4/22/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-28.html)

####Week 15
#####4/27/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-29.html)

#####4/29/2015
Lesson 15: [Introduction to 3D]({{ site.baseurl }}/lessons/lesson-30.html)

<div class="spring-2016">
    {% for lesson in site.lessons %}
       {{ lesson.date }}
       <h2><a href="{{ lesson.url | prepend: site.baseurl }}"><span class="lesson-title">{{ lesson.title }}</span>: <span class="lesson-subtitle">{{ lesson.subtitle }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
