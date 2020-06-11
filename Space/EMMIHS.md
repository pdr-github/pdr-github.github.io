---
layout: spacepost
title: EMMIHS Analog-Mission
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
</style>
</head>

<body>

<p align="center">
  <img src="/assets/images/astrofinalEVA.jpg" alt="Priyanka Analogue astronaut" class="center">
</p>

<button class="accordion">Analogue astronaut missions </button>
<div class="panel">
  <p>
    It is no longer just science-fiction. Humans are really working on concrete projects today in 2020, not only on the exploration but also colonization of space! We are thinking already of building a functional Moon Village by 2050. The Moon Village is an open concept proposed with the goal of a sustainable human and robotic presence on the lunar surface as an ensemble where multiple users can carry out multiple activities.
    <br><br>
    Since it is very difficult for humans to live in space for long periods (unfortunately they cannot seem to be able to live together even on Earth), a lot of research needs to be on surviving out there and hence space agencies are coming together and collaborating on various analogue missions that simulate space environments - such as lunar/martian villages.
  </p>
</div>

<button class="accordion">ILEWG and EMMIHS</button>
<div class="panel">
  <p>
    The <a href="https://en.wikipedia.org/wiki/International_Lunar_Exploration_Working_Group">International Lunar Exploration Working Group</a> (ILEWG) is a public forum sponsored by the world's space agencies (like NASA and ESA) to support international cooperation towards the exploration and utilization of the Moon. As part of research efforts towards the colonization of Moon and creation of a Moon Village (and eventually Mars), ILEWG founded the EuroMoonMars initiative. It comprises of field campaigns in Moon-Mars analogue environments – basically regions on Earth that resemble other planets/space bodies.
    <br><br>
    One such analogue environment is the <a href="https://hi-seas.org/">Hawaii-Space Exploration Analog and Simulation</a> (HI-SEAS). It is located at 2,500 meters in elevation on the slopes of Mauna Loa Volcano in Hawaii, and resembles the surface of the Moon with its lava caves and lava tubes. It is a great training ground for astronaut-simulation missions. Additional fact: HI-SEAS is owned by the founder of the <a href="https://moonbasealliance.com/">International Moonbase Alliance</a> (IMA), Henk Rogers, who is also world-famous for his work in video games (another person who has mixed Space and Art!) EuroMoonMars, IMA and HI-SEAS (<a href="https://emmihs-esa.webnode.nl/">EMMIHS</a>) are collaborating on the EMMIHS campaigns that consist of scientific research, field tests, training and outreach activities.
    <br><br>
    We featured on <a href="https://www.space.com/mock-moon-mission-euromoonmars-hi-seas-hawaii.html">Space.com</a>!
  </p>
</div>

<button class="accordion">My mission</button>
<div class="panel">
  <p align="center">
    <img src="/Portfolio/Commissions/emm3.jpg" alt="EMMIHS-III logo" class="center">
  </p>
  <p>
    Through the European Space Agency EuroMoonMars program, I had the amazing opportunity of being one of the six analogue-astronauts for the third mission, EMMIHS-III. It was a two-week mission in January 2020. I trained under the director of HI-SEAS, Michaela Musilova, as crew-commander, which has been be an incredible addition to my experiences! My main science objectives were experiments in robotics, crew-psychology, space-geology, and navigation. And then, art (I designed the team logo).
    <br><br>
  </p>
</div>

<button class="accordion">Image Gallery</button>
<div class="panel">
  <img src="/Space/EMMIHS3/team.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/Astro_MG_small.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/Cooking.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/ESA_flag.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/EVAprep.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/habdark.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/lavacave1.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/lavacave2.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/MagExperiments.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/MGDBEfilming.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/night.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/PriyankaCave.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/rockoffering.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/Rover.jpg" style="width:100%">
  <img src="/Space/EMMIHS3/Scheduler.jpg" style="width:100%">
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

