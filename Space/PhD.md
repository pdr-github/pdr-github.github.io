---
layout: spacepost
title: Ph.D. Research (GNSS)
---

<img src="/assets/images/gnss_art.png" style="width:100%">

<body>
  <button class="accordion">Abstract</button>
  <div class="panel"> <br>
    {% include Space/PhD/Abstract.md %}
    <br><br><br>
  </div>
  <button class="accordion">PhD Thesis</button>
  <div class="panel" align="center">
  	<p><br>
  		<i> Will be uploaded soon.</i>
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