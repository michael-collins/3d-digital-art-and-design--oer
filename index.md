---
layout: calendar
title: Calendar
---

##Posts
<h5 class="date">
{% for post in site.posts %}
{% capture day %}{{ post.date | date: '%m%d%Y' }}{% endcapture %}
{% capture nday %}{{ post.next.date | date: '%m%d%Y' }}{% endcapture %}

{% if day != nday %}
    {{ post.date | date: "%A, %B %e, %Y" }}
{% endif %}
</h5>
{{ post.content }}
<hr>

{% endfor %}

<h2>Semester</h2>
[Spring 2016]({{ site.baseurl }}/spring-2016)
