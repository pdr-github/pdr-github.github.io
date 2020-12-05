<p align="center">
  <img src="/Portfolio/MoonGal/presenting.jpg" style="width: 100%">
</p>

<div>
  <button class="accordion">Moon Gallery: Context</button>
  <div class="panel">
    <p>
      The International Astronautical Federation (IAF) set up the Committee for the Cultural Utilisation of Space (ITACCUS), with the aim of exploring the importance of cultural activities for human civilizations. In 2019, Priyanka was elected an expert to the committee. Under ITACCUS, ArtMoonMars is an initiative to highlight the importance of artists with respect to space exploration: as message bearers who convey multiple messages of the community including planetary science, life sciences, astronomy, fundamental research, resources utilisation, human spaceflight, peaceful cooperation, economic development, inspiration, training & capacity building.
      <br><br>
      The <a href="http://www.moongallery.eu/">Moon Gallery</a>, by ArtMoonMars, is an international collaborative artwork and a gallery of ideas worth sending to the Moon. Moon Gallery intends to launch 100 artifacts to the Moon within the compact format of a 10 x 10 x 1 cm plate on a lunar lander exterior panelling as early as 2022. As it costs 1 million euros/kg to send something to the Moon, these (smart) artists proposed to hence miniaturise the gallery. The idea is to develop culture for a future interplanetary society in this Petri dish-like gallery.
      <br><br>
      The main team involves Anna Sitnikova (curator, exhibition designer), Elizaveta Glukhova (curator, graphic designer), Bernard Foing (space sector expert and visionary), and Alexander Zaklynsky (gallery founder).
    </p>
  </div>

  <button class="accordion">Artwork: Bhedadīpikā - An Illustration of Duality</button>
  <div class="panel">
    <p>
      The concept of Duality has intrigued mankind since the beginning of civilization, and ancient Vedic texts propose several philosophies on the duality of nature in intriguing detail. <i>Bhedadīpikā</i> is <a href="http://www.moongallery.eu/artist/priyanka-das-rajkakati/"> a visual dialogue</a> based on Priyanka's own duality - as an artist as well as researcher.
      <br><br>
      The artwork comprises of two objects constrained inside a 1cm³ box: a strip of paper with handdrawn phases of the Moon in glow-in-the-dark ink, and a nano-sim card that contains artistic simulations that are coded using Python programming language. Inspired by her Indian roots and Vedic influence, work is named “Bhedadipika – an illustration of Duality”. It plays upon several notions of Duality such as:
      <ul>
        <li>Constraint/Freedom</li>
        <li>Light/Darkness</li>
        <li>Minute/Infinite</li>
        <li>Reality/Illusion</li>
        <li>Randomness/Intent</li>
      </ul>
      <br>
      The animated images are part of a series of algorithmic art titled “Star Cities/Organised Worlds”. These images are created by randomly generated points, but which are constrained to appear on a path defined by equations of <b>epitrochoids and hypotrochoids</b> of various parameters. An epitrochoid or hypotrochoid basically describes the path traced by a spirograph, and is one of the fundamental curves depicting movement in Nature: from celestial orbits to rolling objects. They instill a sense of harmony in the spectator, as the form is naturally pleasing to the eye. The artist imagines that if intelligent life were able to manipulate the formation of galaxies, it would exploit the humble hypotrochoid for inspiration for harmonious forms.
      <br><br>
      For more information on the Moon Gallery Project, please visit the official <a href="http://www.moongallery.eu/">Moon Gallery</a> website.
    </p>
  </div>
</div>

<div align="center">
  <h2>
    Gallery | Discover Bhedadīpikā
  </h2>
  <i>Click on the buttons to change the grid view.</i><br>
  <button onclick="one()">1</button>
  <button onclick="two()">2</button>
  <button onclick="four()">4</button> 
</div>

<div class="row">
  <div class="column">
    <img src="/Portfolio/MoonGal/cube.jpg" alt="Cube" style="width:100%">
    <img src="/Portfolio/MoonGal/hand.jpg" alt="Light and Darkness" style="width:100%">      
    <img src="/Portfolio/MoonGal/moon.jpg" alt="Moon" style="width:100%">
    <img src="/Portfolio/MoonGal/phases.jpg" alt="Phases" style="width:100%">      
  </div>
  <div class="column">
    <img src="/Portfolio/MoonGal/hypo.jpg" alt="Hypo" style="width:100%">
    <img src="/Portfolio/MoonGal/sup.gif" alt="Supernova" style="width:100%">      
    <img src="/Portfolio/MoonGal/nsky.gif" alt="NightSky" style="width:100%">
  </div>
  <div class="column">
    <img src="/Portfolio/Spirographs/epi_43-58-68.gif" alt="Supernova" style="width:100%">
    <img src="/Portfolio/Spirographs/hypo_123-600-123.gif" alt="Supernova" style="width:100%">
    <img src="/Portfolio/MoonGal/glit.gif" alt="NightSky2" style="width:100%">
  </div>
  <div class="column">
    <img src="/Portfolio/Spirographs/epi_30-100-50.gif" alt="Supernova" style="width:100%">
    <img src="/Portfolio/Spirographs/hypo_33-50-50.gif" alt="Supernova" style="width:100%">
  </div>
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
