---
layout: spacepost
title: Space Generation Advisory Council (SGAC)
---

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
