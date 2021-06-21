---
layout: default
title: Ph.D. Research (GNSS)
---

<div class="spacepost" align="center">
  <h1 class="spacepost-title">[Space Projects]</h1>
  <p>
    <a href="/Space/PhD" class=""><button class="button" style="background-color: black; color: white">PhD Research (GNSS)</button></a>
    <a href="/Space/EMMIHS" class=""><button class="button">Analogue-Astronaut</button></a>
    <a href="/Space/MoonGallery"><button class="button">Moon Gallery</button></a>
    <a href="/Space/SGAC"><button class="button">SGAC</button></a>
    <a href="/Space/Xcubesat"><button class="button">X-CubeSat</button></a>
    <hr>
  </p>
  <h1>{{ page.title }}</h1>
  <br>
</div>
<div>
  <img src="/assets/images/gnss_art.png" style="width:100%">

  <body>
    <button class="accordion">About and Abstract</button>
    <div class="panel">
      {% include Space/PhD/Abstract.md %}
      <br><br><br>
    </div>
    <button class="accordion">PhD Thesis</button>
    <div class="panel" align="center">
    	<p><br>
    		<i> Will be uploaded soon.</i>
    	</p>
      <p>
        <a href = "http://www.theses.fr/s222653"> Theses.fr </a>
      </p>
    </div>
    <button class="accordion">Thesis Defense (Slides)</button>
    <div class="panel" align="center">
    	<p><embed src="/Space/PhD/Thesis-slides.pdf" width="100%" height="500px">
    	</p>
    </div>
    <button class="accordion">Publications</button>
    <div class="panel">
      {% include Space/PhD/Publications.md %}
      <br><br>
    </div>
    <button class="accordion">IAC 2019</button>
    <div class="panel"> <br>
      {% include Space/PhD/IAC2019.md %}
      <br>
    </div>
    <button class="accordion">Teaching</button>
    <div class="panel"> <br>
      {% include Space/PhD/Teaching.md %}
      <br>
    </div>
    {% include Scripts/accordion.md %}
  </body>
</div>