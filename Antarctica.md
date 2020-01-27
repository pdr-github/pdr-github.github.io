---
layout: page
title: Antarctica
---

<h2 align="center">
	<b> #HB5 Departure to Antarctica </b>
</h2>
<!-- Display the countdown timer in an element -->
<p id="demo" align="center" style="font-size:40px"></p>

<img src="/Antarctica/banner.jpg" style="width: 100%">

<h2>
	<b>Homeward Bound Initative</b>
</h2>
<p align="justify">
	<a href="https://homewardboundprojects.com.au/about/">Homeward Bound</a> is a global 12-month leadership initiative for women with a background in <b>STEMM (Science, Technology, Engineering, Mathematics and Medicine)</b>, which aims to equip a 1000-strong collaboration of women with the skills to demonstrate a new model of leadership, to create better outcomes for our planet. The programme has been featured multiple times in the <a href="https://homewardboundprojects.com.au/media/">media</a>, including <a href="https://www.forbes.com/sites/emanuelabarbiroglio/2019/11/22/the-largest-ever-womens-expedition-to-antarctica-will-upscale-science-diplomacy/#2f7226237686">Forbes</a>, <a href="https://time.com/longform/women-antarctica-iwd-scientists-explorers/?utm_source=emailshare&utm_medium=email&utm_campaign=email-share-article&utm_content=20190721">Time</a> and <a href="https://www.vogue.com.au/gamechangers/technology-and-business/homeward-bound/news-story/095f8341c7ade07228dfd1da00b12bbf">Vogue</a>.
</p>
<p align="justify">
	For the 2019-20 edition, Homeward Bound is welcoming 80 participants into its fifth program, encompassing more than 25 nationalities and a hugely diverse representation of STEMM fields. Homeward Bound is now nearly halfway towards achieving its vision of creating a global collaboration of 1000 women leaders with STEMM backgrounds.
</p>
<img src="/Antarctica/ant-fiord.jpg">
<p align="center"><cite>Laubeuf Fjord with Webb Island</cite> by Vincent van Zeijst.</p>
<h3>
	<b>Why women in STEMM?</b>
</h3>
<p align="justify">
	Research repeatedly shows that while women demonstrate great integrity and a legacy mindset when it comes to leadership, decision-making and the creation of collaborative and effective teams, they are overwhelmingly under-represented in the traditionally male-dominated professions. This is especially true of women in STEMM fields. For example, in the United States, women currently make up nearly half (48 percent) of the workforce, but hold less than 18 percent of leadership roles at top tech companies.
</p>
<p align="justify">
	Founded in 2016, the program was literally a dream of Australian leadership expert <a href="https://www.vic.gov.au/fabian-dattner">Fabian Dattner</a>, who believed the world needed a program to unlock the leadership potential of outstanding women in STEMM, to upskill and support them to lead, influence and contribute to decision-making about the future of our planet. This 12-month program includes online learning to increase leadership capacity, strategic capability, visibility and collaboration, and culminates in a meeting of all 80 participants in Ushuaia, Argentina before embarking on a life-changing voyage to one of the most ecologically sensitive and inspiring areas on Earth, Antarctica, at the end of 2020.
</p>
<h3>
	<b>Why Antarctica?</b>
</h3>
<p align="justify">
	In the words of Fabian Dattner:
	<p class="message" align="justify">
	"The aim of Homeward Bound has always been to identify and foster outstanding leadership potential in STEMM... It is no accident that we end up in Antarctica, as it is part of the vision. It is where we can see the impact of our crisis of leadership and inaction first-hand. It is sensitive and challenging, awe-inspiring and motivating, and I can think of no more fitting experience for a group of leaders."
</p>
<h3>
	<b>My motivation</b>
</h3>
<p align="justify">
	It's quite an incredible honour that I have been selected for the fifth edition of the initiative. Since being an engineer doesn’t necessarily make one a good leader, I truly look forward to this programme.
	<br><br>
	I feel very strongly for encouraging young girls to pursue Science and dare to dream about Space. Now, more than just good intent, such initiatives require momentum and being part of Homeward Bound will definitely help me with my cause.
	<br><br>
	It is indeed an entire package: a leadership training for women in STEM, networking with future global leaders (some already famous!) and finally, a chance to challenge my physical limits by going to Antarctica.
</p>

<img src="/Antarctica/hb16.jpg" class="center">
<p align="center"><cite>Seventy-six women from around the world, participants on the inaugural Homeward Bound Women In Science Leadership Expedition to Antarctica.</cite> <br><b>PHOTO CREDIT</b> Dr. Shelley Ball.</p>


<script>
// Set the date we're counting down to
var countDownDate = new Date("Nov 12, 2020 15:00:00").getTime();

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