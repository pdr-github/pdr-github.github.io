---
layout: default
title: Space Generation Advisory Council (SGAC)
---

<div class="spacepost" align="center">
  <h1 class="spacepost-title">[Space Projects]</h1>
  <p>
    <a href="/Space/PhD" class=""><button class="button">PhD Research (GNSS)</button></a>
    <a href="/Space/EMMIHS" class=""><button class="button">Analogue-Astronaut</button></a>
    <a href="/Space/MoonGallery"><button class="button">Moon Gallery</button></a>
    <a href="/Space/SGAC"><button class="button" style="background-color: black; color: white">SGAC</button></a>
    <a href="/Space/Xcubesat"><button class="button">X-CubeSat</button></a>
    <hr>
  </p>
  <h1>{{ page.title }}</h1>
  <br>
</div>
<div>
<div>
  <img src="/Space/SGAC/banner.jpg" style="width: 100%">

  <body>
    <button class="accordion">About the SGAC </button>
    <div class="panel"> <br>
      {% include Space/SGAC/About.md %}
    </div>
    <button class="accordion">Our Giant Leap initiative</button>
    <div class="panel"> <br>
      {% include Space/SGAC/OGL.md %}
    </div>
    <button class="accordion">SG[India]2021</button>
    <div class="panel"> <br>
      {% include Space/SGAC/SGIndia.md %}
    </div>  
    <button class="accordion">SGAC PR&Comm team</button>
    <div class="panel"> <br>
      {% include Space/SGAC/PRComm.md %}
      <br>
    </div>  
    {% include Scripts/accordion.md %}
  </body>  
</div>
