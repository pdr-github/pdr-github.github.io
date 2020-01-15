---
layout: page
title: Space Projects
---

  <p align="center">
    <a href="/Space/EMMIHS"> <button><big>EMMIHS Analogue-Mission</big></button> </a>
    <a href="/Space/MoonGallery"> <button><big>Moon Gallery Project</big></button> </a>
    <a href="/Space/OurGiantLeap"> <button><big>Our Giant Leap Initiative</big></button> </a>
  </p>

<br><br>

<img src="/assets/gifs/ns2.gif" style="width: 100%">

<p align="center">(Click on one of the tabs above.)</p>

<!--
<p align="center">
  <a href="/Space/EMMIHS">
    <b>EMMIHS-III Analogue Mission</b>
    <img src="/Portfolio/Commissions/emm3.jpg" style="width:300px" alt="EMMIHS-III logo">
  </a>
  <br>
  <a href="/Space/MoonGallery">
    <b>ESA ILEWG Moon Gallery</b>
    <img src="/assets/gifs/ns2.gif" style="width:300px">
  </a>
  <br>
  <a href="/Space/OurGiantLeap">
    <b>SGAC Our Giant Leap Initiative</b>
    <img src="/Portfolio/Commissions/ogl.png" alt="Our Giant Leap poster" style="width:300px">  
  </a>
</p> 


{% comment %}
<ul class="posts">

{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<div class="row">
	{% for portfolio in site.portfolio %}
		<a href="{{ portfolio.url | prepend: site.baseurl }}">
			<div class="col-xs-12 col-sm-6 col-md-4">
				<div class="panel panel-primary">
					<div class="panel-heading">
						{{ portfolio.title}}
					</div>
					<div class="panel-body">
						{{portfolio.excerpt}}
					</div>
				</div>
			</div>
		</a>
	{% endfor %}	
</div>

  
{% endcomment %}
-->