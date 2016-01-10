---
layout: default
title: Topics
subtitle: Listing
---
<div class="topics">
    {% for topic in site.topics %}
       <h2><a href="{{ topic.url | prepend: site.baseurl }}"><span class="topic-title">{{ topic.title }}</span>: <span class="topic-subtitle">{{ topic.subtitle }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
