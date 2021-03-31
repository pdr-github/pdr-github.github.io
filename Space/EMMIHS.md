---
layout: spacepost
title: EMMIHS Analog-Mission
---

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
    <button class="accordion">Priyanka's mission roles</button>
    <div class="panel"> <br>
      {% include Space/EMMIHS/Mission.md %} <br>
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