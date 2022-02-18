---
layout: artpost
title: Origami
---

<style>
	#origami {
		background-color: black;
		color: white}
</style>
<div>
	{% include Portfolio/Origami/images_thumb.md%}
	<!-- The Modal -->
	<div id="myModal" class="modal">
	  <span class="close cursor" onclick="closeModal()">&times;</span>
	  <div class="modal-content">
	    {% include Portfolio/Origami/images_modal.md%}   
	  </div>
	</div>
	{% include Scripts/modal.md %}
</div>
