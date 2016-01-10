---
layout: default
title: Calendar
---

##Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<h2>Semester</h2>
[Spring 2016]({{ site.baseurl }}/spring-2016)
