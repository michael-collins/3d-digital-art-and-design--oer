---
layout: post
title: Calendar
comments: false
---

{% for post in site.posts %}
{% capture day %}{{ post.date | date: '%m%d%Y' }}{% endcapture %}
{% capture nday %}{{ post.next.date | date: '%m%d%Y' }}{% endcapture %}

{% if day != nday %}
<h5 class="date">{{ post.date | date: "%A, %B %e, %Y" }}</h5>
{% endif %}
<h5><a href="{{ post.url | prepend: site.baseurl }}"><span class="post-title">{{ post.title }}</span></a></h5>
{{ post.content }}
<hr>

{% endfor %}

