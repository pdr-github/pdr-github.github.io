---
layout: aboutpost
title: CV
---

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
  <button class="accordion"> Academic Experience </button>
  <div class="panel"> <br>
    {% include About/CV/Academic_experience.md %}
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

  <script>
  var acc = document.getElementsByClassName("accordion");
  var i;

  for (i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var panel = this.nextElementSibling;
      if (panel.style.maxHeight) {
        panel.style.maxHeight = null;
      } else {
        panel.style.maxHeight = panel.scrollHeight + "px";
      } 
    });
  }
  </script>
</body>
