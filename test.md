---
layout: default
title: 
---

<div>
  <div class="row">
    <div class="column">
      <img src="/Portfolio/Origami/dragon.jpg" alt="Dragon" style="width:100%" 
        onclick="openModal()" class="hover-shadow cursor">
    </div>
    <div class="column">
      <img src="/Portfolio/Origami/butterflygoround.jpg" alt="Butterflies" style="width:100%"
        onclick="openModal()" class="hover-shadow cursor">
    </div>
    <div class="column">
      <img src="/Portfolio/Origami/orchid.jpg" alt="Orchid" style="width:100%"
        onclick="openModal()" class="hover-shadow cursor">    
    </div>
    <div class="column">
      <img src="/Portfolio/Origami/lamp.jpg" alt="Lamp" style="width:100%"
        onclick="openModal()" class="hover-shadow cursor">    
    </div>
  </div>
  <!-- The Modal -->
  <div id="myModal" class="modal">
    <span class="close cursor" onclick="closeModal()">&times;</span>
    <div class="modal-content">
      <div class="mySlides">
        <img src="/Portfolio/Origami/dragon.jpg" alt="Dragon" style="width:100%" >
      </div>
      <div class="mySlides">
        <img src="/Portfolio/Origami/butterflygoround.jpg" alt="Butterflies" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/Portfolio/Origami/orchid.jpg" alt="Orchid" style="width:100%">   
      </div>
      <div class="mySlides">
        <img src="/Portfolio/Origami/lamp.jpg" alt="Lamp" style="width:100%">   
      </div>
    </div>
  </div>
  {% include Scripts/modal.md %}
</div>




