---
layout: article
title: Artificial Intelligence for Autonomous Driving
excerpt: IJCAI-ECAI 2022 Workshop + Challenge
show_info: true
titles:
  en      : &EN       Home
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
key: page-home
article_header:
  type: overlay
  theme: dark
  actions:
    - text: 23 July 2022 | Vienna, Austria (Hybrid)
  background_image:
    gradient: 'linear-gradient(135deg, rgba(52, 140, 96, 0.4), rgba(136, 73, 107, 0.4))'
    src: /assets/images/l2r_banner2.png
---

<style>
.schedule-table-heading {
    display: inline;
    font-weight: bold;
    font-size: 20px;
    color: #999999;
    padding:0 0 20px 0;
}

.schedule-table-timecol {
    padding:0 50px 0 50px;
    display:inline;
}

.schedule-table-eventcol {
    display:inline;
    display:inline-block;
    inline-size: 300px;
}

.schedule-table-contentcol {
    display:inline;
    display:inline-block;
    inline-size: 250px;
    font-size:14px;
    line-height: normal;
}

.schedule-table-row-even {
    display:block;
    width:800px;
    background-color: #EEEEEE;
    padding:10px;
}

.schedule-table-row-odd {
    display:block;
    width:800px;
    padding:10px;
}

.article__header--overlay .overlay {
    min-height: 36rem;
    padding-top: 5rem;
    padding-bottom: 5rem;
}

.article__header {
    margin: 0 0 0 0;
}

.article__header h1 {
    display: inline;
    font-size: 2.5em;
    letter-spacing: -0.04em;
    line-height: 0.9;
    text-shadow: -20px -8px 17px rgb(0 0 0 / 30%);
    word-wrap: break-word;
}

.overlay__excerpt {
    margin: 20px 0 0 0;
}

ul.menu li::after {
    content:"23 July 2022 | Vienna, Austria (Hybrid)";
}

ul.menu a {
    display: none;
}

.pc-column {
    width:270px;
    display:inline-block;
    vertical-align: top;
}

.pc_list_item {
    display:inline-block;
    width:200px;
}

.organiser_profile {
    font-weight:normal;
    color: black;
}

.organiser_profile a:link a:visited a:hover a:active {
    font-weight:normal;
    color: #000000;
}

.organiser_profile p {
    font-weight:normal;
    color: #000000;
}

.logos-organizers {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
}

.img-fluid {
    max-width: 100%;
    height: auto;
}

img {
    vertical-align: middle;
    border-style: none;
}
</style>

<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "Europe/Vienna", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("cet").innerHTML = n
  }, 1000);
</script>

<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-demo').swiper();
  });
</script>

<script>

  var countDownDate = new Date("Feb 15, 2022 23:59:59 UTC").getTime();  
  countDownDate = countDownDate + 1000 * 3600 * 12


  var x = setInterval(function() {


    var now = new Date().getTime();


    var distance = countDownDate - now;


    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);


    var countdown = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";


    if (distance < 0) {
      clearInterval(x);
      countdown = "(expired)";  
    }

    document.getElementById("countdown").innerHTML = countdown

  }, 1000);
</script>

<br>

## About

Welcome to the 2nd <a href="https://ijcai-22.org/" target="_blank">IJCAI</a> Workshop on <i>Artificial Intelligence for Autonomous Driving</i> (AI4AD)!

While there have been significant advances in vehicle autonomy (e.g., perception, trajectory forecasting, planning and control, etc.), it is of paramount importance for autonomous systems to adhere to safety specifications, as any safety infraction in urban and highway driving, or high-speed racing could lead to catastrophic failures. Given this inherent tension between safety and performance, we introduce a new simulation environment in autonomous racing as a particularly challenging proving ground for safe learning algorithms.<br>

We envision this workshop bringing together researchers and industry practitioners from different AI subfields to work towards safer and more robust autonomous technology. We encourage participants to take part in the Challenge by competing for top leaderboard positions, to submit articles for review, and to engage with us at IJCAI 2022.<br>

### Topics covered

<div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Safe reinforcement learning, safe exploration, constrained reinforcement learning, safe learning + control theory</li>
<li>Safety verification, certifying learning-based control under dynamical uncertainty, dependability analysis</li>
<li>Robustness to out-of-distribution road scenes</li>
<li>Learning vehicle dynamics at high-speeds and in unstable regimes</li>
<li>Vision-based perception and scene understanding for autonomous driving</li>
<li>Representation learning for visuomotor control</li>
<li>Transfer learning; simulation to real-world; meta-learning; domain adaptation; *-shot learning; self/semi/weakly-supervised learning; multi-task learning</li>
<li>End-to-end and real-time autonomous driving systems</li>
<li>Novel automotive sensors and their applications</li>
<li>Trajectory forecasting; Behavior prediction of pedestrians, vehicles, and animals</li>
<li>Explainability in autonomous driving</li>
<li>Learning to drive via imitation learning</li>
<li>Learning to drive via distribution awareness</li>
</ul>
</div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Uncertainty propagation through autonomous driving pipelines</li>
<li>Classical planning and control for autonomous driving</li>
<li>Cooperative and competitive multi-agent systems</li>
<li>Visual grounding and its application to autonomous driving</li>
<li>Vision-language navigation for autonomous driving</li>
<li>Audio-visual navigation for autonomous driving</li>
<li>Neuro-symbolic approaches in autonomous driving; Knowledge representation and reasoning</li>
<li>Auditory perception (detection, tracking, segmentation, motion estimation, etc)</li>
<li>Brain-inspired autonomous control systems</li>
<li>Human factors in autonomous driving</li>
<li>AI ethics in autonomous driving</li>
<li>Autonomous driving datasets, simulation, evaluations, and metrics</li>
<li>Connected autonomous driving, vehicle-to-vehicle, vehicle-to-infrastructure communication, digital twins</li>
<li>Autonomous driving for traffic management and emission reduction; intelligent transportation systems</li>
</ul>
</div>
</div>

## Dates

### Paper + Presentation Deadlines

Note: all deadlines are in <b>Central European Time (CET), UTC +1, Paris, Brussels, Vienna</b>.

<div>
<b>Submissions open:</b> 3 March 2022<br>
<b>Submissions due:</b> <p style="display:inline; text-decoration:line-through;">13 May 2022</p><p style="display:inline; color:red;">&nbsp;20 May 2022</p><br>
<b>Notification:</b> 3 June 2022<br>
<b>Camera Ready</b>: 17 June 2022<br>
<b>Oral/Poster video upload</b>: 1 July 2022
</div>

### Workshop Event (IJCAI-ECAI 2022 Workshop #48)

<b>Date:</b> 23 July 2022<br>
<b>Location:</b> "Lehar 3" room of the <i>Messe Wien Exhibition and Congress Center</i> in Vienna, Austria.<br>

> <b>Messe Wien</b><br>
> Hall B, entrance Congress Center<br>
> Messeplatz 1<br>
> A-1020 Vienna<br>
> Metro stop U2 "Messe Prater"

Additional venue information: <a href="https://ijcai-22.org/venue/" target="_blank">https://ijcai-22.org/venue/</a><br>

Additional schedule information: <a href="https://www.ijcai-22.org/ijcai-2022-schedule/" target="_blank">https://www.ijcai-22.org/ijcai-2022-schedule/</a>

## Workshop Schedule

Saturday, 23 July, 2022. All times are in Central European Time (CET). Current time is <span id="cet"></span>.

<div style="display:block; width:900px; padding:20px; border:solid 4px #CCCCCC;">
<div class="schedule-table-heading" style="margin-left:57px; display:inline-block; inline-size:100px;">Time</div>
<div class="schedule-table-heading" style="display:inline-block; inline-size:295px;">Event</div>
<div class="schedule-table-heading">Content</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">08:50</div>
<div class="schedule-table-eventcol">Welcome</div>
<div class="schedule-table-contentcol">Opening Remarks</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:00</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/max_kumskoy.png" alt="Max Kumskoy">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/ivan_zhukov.png" alt="Ivan Zhukov">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Max Kumskoy</p>
<p style="margin:0 0 0 10px; font-size:10px;">ARRIVAL</p>
<p style="margin:10px 0 0 10px;">Ivan Zhukov</p>
<p style="margin:0 0 0 10px; font-size:10px;">ARRIVAL</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><i>ARRIVAL Vehicle Simulation: Full-stack Simulator for Research, Development, and Testing of any Vehicle, Vehicle System, or Feature</i></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/sahika_genc.png" alt="Sahika Genc">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sahika Genc</p>
<p style="margin:0 0 0 10px; font-size:10px;">Amazon AWS</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/AOOZTR2fZdE" target="_blank"><i>Deep Reinforcement Learning for Autonomous Driving with AWS DeepRacer</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">10:00</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>
<!--div class="schedule-table-contentcol">Paper IDs: 1, 4, 5, 6, 7, 12, 13, 14, 17</div-->
<div class="schedule-table-contentcol"><a href="https://app.gather.town/app/LKQOfjZkcrh2dfm4/AI4AD" target="_blank"><b>Gathertown</b></a> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">11:00</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px; ">Shunli Ren</p>
<p style="margin:0 0 0 10px; font-size:10px;">SJTU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a href="https://youtu.be/3cIWpMrsyeE" target="_blank"><i>Robust Collaborative Perception against Communication Interruption</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Balint Gyevnar</p>
<p style="margin:0 0 0 10px; font-size:10px;">U Edinburgh</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a href="https://youtu.be/gmjylztszZA" target="_blank"><i>A Human-Centric Method for Generating Causal Explanations in Natural Language for Autonomous Vehicle Motion Planning</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">11:30</div>
<div class="schedule-table-eventcol">Lunch Break</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">13:00</div>
<div class="schedule-table-eventcol">Autonomous Racing Virtual Challenge: Contributed Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Matthew R Howe</p>
<p style="margin:0 0 0 10px; font-size:10px;">U Adelaide</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a href="https://youtu.be/bTBk8MFdIOA" target="_blank"><i>The Edge of Disaster: A Battle Between Autonomous Racing and Safety</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Lachlan Mares</p>
<p style="margin:0 0 0 10px; font-size:10px;">U Adelaide</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a href="https://youtu.be/5oYUBg9SZEk" target="_blank"><i>Learn 2 Rage: Experiencing The Emotional Roller Coaster That Is Reinforcement Learning</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">13:30</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Mihaela Catalina Stoian</p>
<p style="margin:0 0 0 10px; font-size:10px;">Oxford</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a href="https://youtu.be/_-Ll5d1VQXY" target="_blank"><i>ROAD-R: The Autonomous Driving Dataset with Logical Requirements</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Soumith Udatha</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><i>Safe Reinforcement Learning with Probabilistic Control Barrier Functions for Ramp Merging</i></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">14:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/changliu_liu.png" alt="Changliu Liu">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Changliu Liu</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/XsizJBWdz-A"><i>Safe Learning, Prediction, and Coordination for Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">14:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/madhur_behl.png" alt="Madhur Behl">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Madhur Behl</p>
<p style="margin:0 0 0 10px; font-size:10px;">UVA</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/0wdf8anWf3k" target="_blank"><i>Bringing AI Up To Speed with Autonomous Racing</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">15:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/ding_zhao.png" alt="Ding Zhao">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Ding Zhao</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/TjxgChqlXF8"><i>Developing Trustworthy AI for Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">15:30</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>
<!--div class="schedule-table-contentcol">Paper IDs: 1, 4, 5, 6, 7, 12, 13, 14, 17</div-->
<div class="schedule-table-contentcol"><a href="https://app.gather.town/app/LKQOfjZkcrh2dfm4/AI4AD" target="_blank"><b>Gathertown</b></a> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">16:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/johannes_betz.png" alt="Johannes Betz">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Johannes Betz</p>
<p style="margin:0 0 0 10px; font-size:10px;">UPenn</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/uFSLC3ylUW4"><i>Learning to Handle Autonomous Vehicles at the Limit - Experiences from Roborace and the Indy Autonomous Challenge</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">17:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/rowan_mcallister.png" alt="Rowan McAllister">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Rowan McAllister</p>
<p style="margin:0 0 0 10px; font-size:10px;">TRI</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a href="https://youtu.be/zaOAfv7YYE0" target="_blank"><i>Robust Behavior Models for Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">17:30</div>
<div class="schedule-table-eventcol">Conclusion</div>
<div class="schedule-table-contentcol">Closing Remarks</div>
</div>

</div>

## Speakers

<div style="display:block; padding:10px 0 0 0; width:900px;">

<a href="https://arrival.com/us/en" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:80px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/max_ivan.png" alt="Max Kumskoy, Ivan Zhukov">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Max Kumskoy, Ivan Zhukov</p>
<p style="margin:0 0 0 10px; font-size:10px;">Automated Driving Systems<br>ARRIVAL</p>
</div>
</div>
</a>

<a href="https://www.amazon.science/author/sahika-genc" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/sahika_genc.png" alt="Sahika Genc">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sahika Genc</p>
<p style="margin:0 0 0 10px; font-size:10px;">Principal Scientist<br>Amazon AWS</p>
</div>
</div>
</a>

<a href="https://www.cs.cmu.edu/~cliu6/index.html" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/changliu_liu.png" alt="Changliu Liu">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Changliu Liu</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>Carnegie Mellon University</p>
</div>
</div>
</a>

<a href="https://www.madhurbehl.com/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/madhur_behl.png" alt="Madhur Behl">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Madhur Behl</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>University of Virginia</p>
</div>
</div>
</a>


<a href="https://safeai-lab.github.io/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/ding_zhao.png" alt="Ding Zhao">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Ding Zhao</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>Carnegie Mellon University</p>
</div>
</div>
</a>

<a href="https://joebetz.science/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/johannes_betz.png" alt="Johannes Betz">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Johannes Betz</p>
<p style="margin:0 0 0 10px; font-size:10px;">Postdoctoral Researcher<br>University of Pennsylvania</p>
</div>
</div>
</a>

<a href="https://rowanmcallister.github.io/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/rowan_mcallister.png" alt="Rowan McAllister">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Rowan McAllister</p>
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Scientist<br>Toyota Research Institute</p>
</div>
</div>
</a>

</div>

## Challenge

We also feature an exciting and new AI Challenge in high-speed autonomous racing. Here, the goal is to evaluate the joint safety, performance, and generalisation capabilities of perception and control algorithms, as they operate simulated Formula-style racing vehicles at their physical limits! The Learn-to-Race Autonomous Racing Virtual Challenge is now active. <a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank">Participate now</a>!

<!--div class="swiper swiper-demo">
  <div class="swiper__wrapper">
    <div class="swiper__slide">
      <img src="{{ site.baseurl }}/assets/images/challenge/lvms-overhead.png" alt="LVMS">
    </div>
    <div class="swiper__slide">
      <img src="{{ site.baseurl }}/assets/images/challenge/anglesey-overhead.png" alt="LVMS">
    </div>
    <div class="swiper__slide">
      <img src="{{ site.baseurl }}/assets/images/challenge/thruxton-overhead.png" alt="LVMS">
    </div>
  </div>
  <div class="swiper__button swiper__button--prev fas fa-chevron-left"></div>
  <div class="swiper__button swiper__button--next fas fa-chevron-right"></div>
</div-->

<div style="display:block; width:100%;">
<div style="display:block; margin-bottom:7px;">
<div style="display:inline; margin-right:5px;"><a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank"><img width="410px" height="226px" src="{{ site.baseurl }}/assets/images/challenge/banner-l2rc-text.png" alt="L2R Autonomous Racing Virtual Challenge: Safe Learning for Autonomous Driving"></a></div>
<div style="display:inline;"><a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank"><img width="410px" height="226px" src="{{ site.baseurl }}/assets/images/challenge/banner-lvms.png" alt="L2R Autonomous Racing Virtual Challenge: Safe Learning for Autonomous Driving"></a></div>
</div>
<div style="display:block;">
<div style="display:inline; margin-right:5px;"><a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank"><img width="410px" height="226px" src="{{ site.baseurl }}/assets/images/challenge/banner-driving.gif" alt="L2R Autonomous Racing Virtual Challenge: Safe Learning for Autonomous Driving"></a></div>
<div style="display:inline;"><a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank"><img width="410px" height="226px" src="{{ site.baseurl }}/assets/images/challenge/banner-car.png" alt="L2R Autonomous Racing Virtual Challenge: Safe Learning for Autonomous Driving"></a></div>
</div>
</div>

<a href="https://www.aicrowd.com/challenges/learn-to-race-autonomous-racing-virtual-challenge" target="_blank"><img src="{{ site.baseurl }}/assets/images/challenge/aicrowd_challenge_steps.gif" alt="Steps to victory!"></a>

## Organisers

<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://www.linkedin.com/in/jonmfrancis/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/jonathan_francis.png" alt="Jonathan Francis">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jonathan Francis</p>
<!--p style="margin:0 0 0 10px;">CMU + Bosch</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Scientist at Bosch Research; domain knowledge-enhanced representation learning, applied to robotics and autonomous driving</p>
</div>
</div>
</a>

<a href="https://xinshuoweng.com/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/xinshuo_weng.png" alt="Xinshuo Weng">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Xinshuo Weng</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Scientist at NVIDIA Research; focusing on 3D computer vision and generative models for autonomous systems</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/hitesharora11" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/hitesh_arora.png" alt="Hitesh Arora">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Hitesh Arora</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Researcher at Amazon, focusing on multimodal perception and reinforcement learning, applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/bingqing-chen-631b754a/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/bingqing_chen.png" alt="Bingqing Chen">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Bingqing Chen</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Research Scientist at Bosch Research, focusing on constraint-based optimisation, physical mechanisms, and safe learning, applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/sidgan/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/siddha_ganju.png" alt="Siddha Ganju">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Siddha Ganju</p>
<!--p style="margin:0 0 0 10px;">NVIDIA</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Researcher and Data Scientist at NVIDIA, focusing on computer vision optimization for vehicle autonomy and medical instruments</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/bhat-manoj/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/manoj_bhat.png" alt="Manoj Bhat">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Manoj Bhat</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Researcher at Amazon, focusing on Neural Radiance fields, reinforcement learning, and representation learning applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://danielomeiza.github.io/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/daniel_omeiza.png" alt="Daniel Omeiza">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Daniel Omeiza</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at Oxford, focusing on explainable AI and decision-making, in autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.cs.cmu.edu/~./jeanoh/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/jean_oh.png" alt="Jean Oh">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jean Oh</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Professor in Robotics Institute at CMU and Director of Bot Intelligence Group; multimodal perception, navigation, and artificial intelligence</p>
</div>
</div>
</a>

<a href="https://www.cs.cmu.edu/~ehn/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/eric_nyberg.png" alt="Eric Nyberg">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Eric Nyberg</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Professor of Computer Science at CMU and Program Director, Masters of Computational Data Science; hybrid reasoning systems and artificial intelligence</p>
</div>
</div>
</a>

<a href="https://sylviaherbert.com" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/sylvia_herbert.png" alt="Sylvia Herbert">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sylvia Herbert</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor at UCSD and Director of Safe Autonomous Systems Lab; uncertainty modeling in control, safety-aware learning, autonomy</p>
</div>
</div>
</a>

</div>

## Program Committee

<!-- column 1 -->
<div class="pc-column">
<ul>
<li>Raghuram Annasamy (+<b>ER</b>, <b>TR</b>)</li>
<li>Johannes Betz (<b>SMR</b>)</li>
<li>Wenhao Ding</li>
<li>Nemanja Djuric</li>
<li>Jaime Fisac (<b>SMR</b>)</li>
<li>Xiangyu Gao (+<b>ER</b>)</li>
<li>Shivam Goel</li>
<li>Sidharth Kathpal</li>
<li>Anirudh Koul</li>
</ul>
</div>

<!-- column 2 -->
<div class="pc-column" style="margin:0 30px 0 0;">
<ul>
<li>Tanmay Kulkarni</li>
<li>Jingyuan Li</li>
<li><a href="https://navars.xyz/" target="_blank">Ingrid Navarro</a> (<b>TR</b>)</li>
<li>Aarati Noronha</li>
<li>Alessandro Oltramari (<b>TR</b>)</li>
<li>Karthik Paga (<b>ER</b>, <b>TR</b>)</li>
<li>Ehsan Qasemi (<b>TR</b>)</li>
<li>João Semedo</li>
</ul>
</div>

<!-- column 3 -->
<div class="pc-column">
<ul>
<li>Yash Shukla</li>
<li>Jayant Tamarapalli</li>
<li>Gyan Tatiya</li>
<li>Yujie Wei (+<b>ER</b>)</li>
<li><a href="https://github.com/weirayao" target="_blank">Weiran Yao</a></li>
<li><a href="https://xyaoab.github.io/" target="_blank">Xinjie Yao</a></li>
<li>Sahiti Yerramilli</li>
<li>Ding Zhao (<b>SMR</b>)</li>
</ul>
</div>

<!-- column 4 >
<div style="width:201px; display:inline-block; vertical-align: top;">
<ul>
</ul>
</div-->

---

<b>ER</b> — <i>Recognises PC member who served ("+" additionally) as an Emergency Reviewer.</i><br>
<b>TR</b> — <i>Recognises PC member who, according to Chair ratings, ranked in the Top 16% of Reviewers.</i><br>
<b>SMR</b> — <i>Recognises PC member who agreed to provide their services as a Senior Meta-Reviewer.</i>

## Sponsors

<img src="{{ site.baseurl }}/assets/images/sponsors/sponsor_banner.png">

<!--
<div class="col-lg-12 col-xl-6">
            <div class="logos-organizers">
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/arrival_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/cmu_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/aicrowd_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/aws_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png">
              </div>
            </div>
          </div>
-->
<!--
<div style="width:900px; display:inline-block;">
<img style="height:100px; width:186px;" src="{{ site.baseurl }}/assets/images/sponsors/arrival_logo.png">
<img style="height:100px; width:157px;" src="{{ site.baseurl }}/assets/images/sponsors/cmu_logo.png">
<img style="height:100px; width:100px;" src="{{ site.baseurl }}/assets/images/sponsors/aicrowd_logo.png">
<img style="height:100px; width:98px;" src="{{ site.baseurl }}/assets/images/sponsors/aws_logo.png">
<img style="height:100px; width:272px;" src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png">
<img style="height:100px; width:354px;" src="{{ site.baseurl }}/assets/images/sponsors/honda_logo.png">
</div>
-->
