---
layout: topic
title: Topics
subtitle: Listing
comments: false
---
<div class="topics">
    {% for topic in site.topics %}
       <h2><a href="{{ topic.url | prepend: site.baseurl }}"><span class="topic-title">{{ topic.title }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
<hr>
{% if day != nday %}
<h5 class="post-date">{{ post.date | date: "%A, %B %e, %Y" }}</h5>
{% endif %}
<h5 class="post-title"><a href="{{ post.url | prepend: site.baseurl }}"><span class="post-title">{{ post.title }}</span></a><span class="post-type {{post.categories}}"> ( {{post.categories}} )</span></h5>
<div class="post-content">{{ post.excerpt }}</div>
{% endfor %}