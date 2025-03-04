---
layout: default
title: Drone eskola irekia
permalink: /argitalpenak
---

<div class="posts-list">

    {% for post in site.posts %}

       {% if post.lang == "eu" %}

           <hr>

    	   <div class="post">

    	   	<a href=" {{ post.url }} ">

		        {{ post.title }} ({{ post.date | date: "%Y/%m/%d" }})
	      
			<img src="{{ post.image }}" alt="{{ post.title }}" class="post-image">


	  	</a>
	  	<p>
			{{ post.excerpt }}
	  	</p>

	   </div>

      {% endif %}

    {% endfor %}

</div>