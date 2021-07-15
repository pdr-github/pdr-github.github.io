---
layout: default
title: EMMIHS Analog-Mission
---

<div class="spacepost" align="center">
  <h1 class="spacepost-title">[Space Projects]</h1>
  <p>
    <a href="/Space/PhD" class=""><button class="button">PhD Research (GNSS)</button></a>
    <a href="/Space/EMMIHS" class=""><button class="button" style="background-color: black; color: white">Analogue-Astronaut</button></a>
    <a href="/Space/MoonGallery"><button class="button">Moon Gallery</button></a>
    <a href="/Space/SGAC"><button class="button">SGAC</button></a>
    <a href="/Space/Xcubesat"><button class="button">X-CubeSat</button></a>
    <hr>
  </p>
  <h1>{{ page.title }}</h1>
  <br>
</div>
<div>

  <img src="/Space/EMMIHS3/astrofinalEVA.jpg" alt="Priyanka Analogue astronaut">

  <body>
    <div>
      <button class="accordion">Analogue astronaut missions </button>
      <div class="panel"> <br>
        {% include Space/EMMIHS/About.md %} <br>
      </div>
      <button class="accordion">ILEWG and EMMIHS</button>
      <div class="panel"> <br>
        {% include Space/EMMIHS/ILEWG.md %} <br>
      </div>
      <button class="accordion">Publications</button>
      <div class="panel"> <br>
        {% include Space/EMMIHS/Publications.md %} <br>
      </div>  
    </div>
    <div> <br>
      {% include Space/EMMIHS/Gallery.md %} <br>
    </div>  
  </body>
  {% include Scripts/accordion.md %}
</div>