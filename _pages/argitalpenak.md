---
layout: default
title: Drone eta urrutiko gailuen inguruko azken berriak eta argitalpenak
permalink: /argitalpenak
---

<h1 class="project-tagline">Jarraian drone eta urrutiko gailuen albisteak aurkituko dituzu </h1>

Albiste hauek guztiak drone eskolaren artikuluetan zehar zitatzen dira, baina guztiak hemen pilatu ditugu irakurgarritasuna areagotzeko.
Artikulu berri bat drone eskolan txertatzeko interesa baduzu, [jarri harremanetan gurekin]({{ site.baseurl }}/harremanetarako){:target="_blank"}.

<div class="posts-list">

    {% for post in site.posts %}

        <hr style="height: 10px;" />

    	<div class="post">

          <div class="post-image-wrapper">
	     <a href=" {{ post.url }} ">
		<img class="post-image" src="{{ post.image }}" alt="{{ post.title }}" >
	     </a>
	  </div>

	  <div class="post-content">
	     <h2 class="project-tagline post-title">
	    	<a href=" {{ post.url }} "> {{ post.title }} </a>
	     </h2>

	     <p> {{ post.excerpt }} </p>
             <a href=" {{ post.url }} "> Albiste osoa irakurri </a>

	  </div>

        </div>

    {% endfor %}

</div>