---
layout: default
title: News
---

<div class="aboutpost">
  <h1 class="aboutpost-title" align="center">[About]</h1>
  <p align="center">
    <!-- a href="/About/Intro"><button class="button">A few words</button></a -->
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

<!--
<br><br>

<div align="center" >
  <iframe width="560" height="315" src="https://www.youtube.com/embed/BgeJFqWvfPY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br><br>


<div class="cards">
  <a href="https://www.forbesindia.com/article/30-under-30-2021/priyanka-das-rajkakati-mixing-science-and-art/66429/1">
    <div class="card">
      <img src="/Media/f30u30.jpg" object-fit="cover">
      <div class="cardtext">
        | February 12, 2021 | <br>
        Forbes India 30 under 30 | Priyanka Das Rajkakati: Mixing science and art 
      </div>
    </div>
  </a>
  <a href="https://www.polytechnique.edu/en/content/priyanka-das-rajkakati-x2013-joins-2021-forbes-india-30-under-30-list">
    <div class="card">
      <img src="/Media/xforbes-feb21.jpg" object-fit="cover">
      <div class="cardtext">
        | February 12, 2021 | <br>
        Ecole Polytechnique | Priyanka Das Rajkakati (X2013) joins the 2021 Forbes India 30 under 30 list
      </div>
    </div>
  </a>
  <a href="https://www.oneindia.com/videos/living-in-space-aerospace-engineer-artist-talks-about-living-her-dreams-1067924.html">
    <div class="card">
      <img src="/Media/oneindia.jpg" object-fit="cover">
      <div class="cardtext">
        | July 28, 2020 | <br>
        Living in space| Aerospace engineer & artist talks about living her dreams
      </div>
    </div>
  </a>
  <a href="https://www.space.com/mock-moon-mission-euromoonmars-hi-seas-hawaii.html">
    <div class="card">
      <img src="/Media/spacedotcom2.jpg" object-fit="cover">
      <div class="cardtext">
        | January 27, 2020 | <br>
        European scientists are taking a mock Moon mission in Hawaii right now
      </div>
    </div>
  </a>
  <a href="https://indianexpress.com/article/technology/science/indian-origin-woman-scientist-heads-to-antarctica-eyes-space-6077006/">
    <div class="card">
      <img src="/Media/indianexpress1.jpg" object-fit="cover">
      <div class="cardtext">
        | October 19, 2019 | <br>
        Indian-origin woman scientist heads to Antarctica, eyes space
      </div>
    </div>
  </a>
</div>
-->
