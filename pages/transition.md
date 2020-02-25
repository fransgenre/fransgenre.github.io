---
layout: page
title: La transition
permalink: /transition
---
# La transition


## Ressources disponibles sur ce wiki
<div class="section-index">
    <hr class="panel-line">
    {% for post in site.transition  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>

## Ressources Externes
