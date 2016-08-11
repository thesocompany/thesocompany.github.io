---
layout: page
title: List of posts
permalink: /updates/
---

<div class="row">
<div class="small-12 medium-11 medium-centered columns" markdown="1">

<ul class="posts">

    {% for post in site.posts %}
        <li><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
    
</ul> 

</div>
</div>