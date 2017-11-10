---
layout: page
title: List of posts
permalink: /dispatch/
---

<div class="row">
<div class="small-12 medium-centered columns" markdown="1">

<ul class="posts">

    {% for post in site.posts %}
    <li>
			<h4><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h4>
    		<i>{{ post.excerpt }}</i>
    </li>
    {% endfor %}
    
</ul> 

</div>
</div>
