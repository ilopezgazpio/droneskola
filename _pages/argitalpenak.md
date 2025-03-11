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
		   	<h2 class="project-tagline">       {{ post.title }}   ({{ post.date | date: "%Y/%m/%d" }}) 		</h2>

			<img src="{{ post.image }}" alt="{{ post.title }}" class="post-image">


	  	</a>
	  	<p>
			{{ post.excerpt }}

	    	   	<a href=" {{ post.url }} ">
			   Irakurtzen jarraitu
			</a>
	  	</p>

	   </div>

      {% endif %}

    {% endfor %}

</div>