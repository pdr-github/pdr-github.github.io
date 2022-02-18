---
layout: artpost
title: Illustrations
---

<style>
	#illustrations {
		background-color: black;
		color: white}
</style>
<div>
	{% include Portfolio/Paintings/images_thumb.md%}
	<!-- The Modal -->
	<div id="myModal" class="modal">
	  <span class="close cursor" onclick="closeModal()">&times;</span>
	  <div class="modal-content">
	    {% include Portfolio/Paintings/images_modal.md%}   
	  </div>
	</div>
	{% include Scripts/modal.md %}
</div>

