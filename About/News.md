---
layout: default
title: News
---

<div class="aboutpost">
  <h1 class="aboutpost-title" align="center">[About]</h1>
  <p align="center">
    <a href="/About/Bio"><button class="button">Bio</button></a>
    <a href="/About/CV"><button class="button">CV</button></a>
    <a href="/About/News"><button class="button" style="background-color: black; color: white">News</button></a>
    <a href="/About/Contact"><button class="button">Contact</button></a>  <hr>
  </p>
  <h1 align="center">{{ page.title }}</h1>
  <br>
</div>
<div>
  <a href="https://www.forbesindia.com/article/30-under-30-2021/priyanka-das-rajkakati-mixing-science-and-art/66429/1">
    <img src="/assets/images/forbes.jpg" style="width: 100%">
  </a>

  <h2>Featured</h2>
  <div> <br>
    {% include About/News/Featured.md %}
  </div>

  <br>
  <h2>News archive</h2>
  <body>
    <button class="accordion">2021</button>
    <div class="panel"> <br>
      {% include About/News/2021.md %}
      <br>
    </div>
    <button class="accordion">2020</button>
    <div class="panel"> <br>
      {% include About/News/2020.md %}  
      <br>
    </div>
    <button class="accordion">2019 and earlier</button>
    <div class="panel"> <br>
      {% include About/News/2019-and-before.md %}  
      <br>
    </div>
    {% include Scripts/accordion.md %}
  </body>
</div>
