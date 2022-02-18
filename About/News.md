---
layout: aboutpost
title: Press
---

<style>
  #press {
    background-color: black;
    color: white}
</style>
<div>

  <img src="/assets/images/contact.jpg" style="width: 100%">

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
