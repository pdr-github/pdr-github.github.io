---
layout: aboutpost
title: CV
---

<script> actbtn("btncv") </script>
<div>
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