---
layout: default
title: CV
---

<div class="aboutpost">
  <h1 class="aboutpost-title" align="center">[About]</h1>
  <p align="center">
    <a href="/About/Bio"><button class="button">Bio</button></a>
    <a href="/About/CV"><button class="button" style="background-color: black; color: white">CV</button></a>
    <a href="/About/News"><button class="button">News</button></a>
    <a href="/About/Contact"><button class="button">Contact</button></a>  <hr>
  </p>
  <h1 align="center">{{ page.title }}</h1>
  <br>
</div>
<div>
  <img src="/assets/images/astrofinalEVA_cut.jpg" style="width: 100%">

  <body>
    <button class="accordion"> Education </button>
    <div class="panel"> <br>
      {% include About/CV/Education.md %}
      <br>
    </div>
    <button class="accordion"> Honors </button>
    <div class="panel">
      {% include About/CV/Honors.md %}
      <br><br>
    </div>
    <button class="accordion"> Professional Experience </button>
    <div class="panel"> <br>
      {% include About/CV/Professional_experience.md %}
      <br><br><br>
    </div>
    <button class="accordion"> Art, Leadership & Volunteering </button>
    <div class="panel">
      {% include About/CV/Art-Leadership_experience.md %}
      <br>
    </div>
    <button class="accordion"> Publications </button>
    <div class="panel"> <br>
      {% include About/CV/Publications.md %}
      <br><br><br>
    </div>
    <button class="accordion"> Talks </button>
    <div class="panel">
      {% include About/CV/Talks.md %}
      <br>
    </div>
    <button class="accordion"> Teaching </button>
    <div class="panel">
      {% include About/CV/Teaching.md %}
      <br>
    </div>
    {% include Scripts/accordion.md %}
  </body>
</div>