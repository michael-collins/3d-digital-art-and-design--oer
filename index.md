---
layout: calendar
title: Calendar
---

{% for post in site.posts %}
{% capture day %}{{ post.date | date: '%m%d%Y' }}{% endcapture %}
{% capture nday %}{{ post.next.date | date: '%m%d%Y' }}{% endcapture %}

{% if day != nday %}
<h5 class="date">{{ post.date | date: "%A, %B %e, %Y" }}</h5>
{% endif %}
<h2><a href="{{ post.url | prepend: site.baseurl }}"><span class="topic-title">{{ post.title }}</span></a></h2>
{{ post.content }}
<hr>

{% endfor %}

<h2>Semester</h2>
[Spring 2016]({{ site.baseurl }}/spring-2016)
