---
layout: default
title: Presentations
subtitle: Listing
---
<div class="presentations">
    {% for presentation in site.presentations %}
       <h2><a href="{{ presentation.url | prepend: site.baseurl }}"><span class="presentation-title">{{ presentation.title }}</span>: <span class="presentation-subtitle">{{ presentation.subtitle }}</span></a></h2>
       <p>{{content}}</p>
    {% endfor %}
</div>
