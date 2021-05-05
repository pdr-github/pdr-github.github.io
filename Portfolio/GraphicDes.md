---
layout: default
title: Graphic Design
---

<div class="artpost" align="center">
	<h1 class="artpost-title">[Art Portfolio]</h1>
	<a href="/Portfolio/MoonGallery"><button class="button">Moon Gallery Project</button></a>
	<a href="/Portfolio/Paintings"><button class="button">Paintings & Illustrations</button></a>
	<a href="/Portfolio/GraphicDes"><button class="button" style="background-color: black; color: white">Graphic Design</button></a>
	<a href="/Portfolio/Origami"><button class="button">Origami</button></a>
	<hr>
	<h1>{{ page.title }}</h1>
	<br>
</div>
<div>
	{% include Portfolio/GraphicDes/images_thumb.md%}
	<!-- The Modal -->
	<div id="myModal" class="modal">
	  <span class="close cursor" onclick="closeModal()">&times;</span>
	  <div class="modal-content">
	    {% include Portfolio/GraphicDes/images_modal.md%}   
	  </div>
	</div>
	{% include Scripts/modal.md %}
</div>
