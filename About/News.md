---
layout: aboutpost
title: News
---
<h1>Featured</h1><br>

<div>

  <p>
    <b> TechRound UK </b> | March 08, 2021
    <br> <a href="https://techround.co.uk/international-womens-day/priyanka-das-rajkakati-2021-forbes-india-30-under-30-winner/">
      International Women’s Day 2021: Inspiring Quotes and Advice - Priyanka Das Rajkakati
    </a>
  </p>

  <p>
    <b> IIFTO </b> | March 08, 2021 
    <br> <a href="https://www.youtube.com/watch?v=BgeJFqWvfPY">
      Journey from India to Space | Gems of India Series 
    </a>
  </p>

  <p>
    <b> Forbes India 30 under 30 </b> | February 12, 2021
    <br> <a href="https://www.forbesindia.com/article/30-under-30-2021/priyanka-das-rajkakati-mixing-science-and-art/66429/1">
      Priyanka Das Rajkakati: Mixing science and art 
    </a>
  </p>

  <p>
    <b> Ecole Polytechnique </b> | February 12, 2021
    <br> <a href="https://www.polytechnique.edu/en/content/priyanka-das-rajkakati-x2013-joins-2021-forbes-india-30-under-30-list">
      Priyanka Das Rajkakati (X2013) joins the 2021 Forbes India 30 under 30 list
    </a>
  </p>

  <p>
    <b> One India </b> | July 28, 2020
    <br> <a href="https://www.oneindia.com/videos/living-in-space-aerospace-engineer-artist-talks-about-living-her-dreams-1067924.html">
      Living in space| Aerospace engineer & artist talks about living her dreams
    </a>
  </p>

  <p>
    <b> Space.com </b> | January 27, 2020
    <br> <a href="https://www.space.com/mock-moon-mission-euromoonmars-hi-seas-hawaii.html">
      European scientists are taking a mock Moon mission in Hawaii right now
    </a>
  </p>

  <p>
    <b> Indian Express </b> | October 19, 2019
    <br> <a href="https://indianexpress.com/article/technology/science/indian-origin-woman-scientist-heads-to-antarctica-eyes-space-6077006/">
      Indian-origin woman scientist heads to Antarctica, eyes space
    </a>
  </p>

  <p>
    <b>French Embassy in India </b> | April 12, 2018
    <br> <a href="https://in.ambafrance.org/Testimony-of-an-Indian-Student-Priyanka-Das-in-France">
      Testimony of an Indian Student Priyanka Das in France
    </a>
  </p>

</div>



<br><br>
<h1>News archive</h1>
<br>

<body>

<button class="accordion">2021</button>
<div class="panel"> <br>
  {% include News/2021.md %}
  <br>

</div>

<button class="accordion">2020</button>
<div class="panel"> <br>
  {% include News/2020.md %}  
  <br>

</div>

<button class="accordion">2019 and earlier</button>
<div class="panel"> <br>
  {% include News/2019-and-before.md %}  
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

<script>
// Set the date we're counting down to
var countDownDate = new Date("Nov 12, 2021 15:00:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d : " + hours + "h : "  + minutes + "m : " + seconds + "s";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "Wait is over!";
  }
}, 1000);
</script>

</body>


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
