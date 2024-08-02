---
layout: page
title: Nixie Tube Watch
description: DIY watch with Nixie tubes from the 1950s. 
img: assets/img/NixieTubeVideoThumbnail.png
importance: 1
category: fun
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/nixieWatch.jpg" title="Nixie Watch" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Here's my watch up and running. I planned this out to be a summer project before the start of uni, but it ended up taking over half a year lol.\n
</div>

<b>Objective: Build an analog watch from scratch using cathode ray Nixie tubes from the 1950s.</b>
<ul>
  <li>Designed printed circuit boards to keep the form factor of the watch as compact as possible.</li>
  <li>Created a Qi standard charging module for the watch to charge wirelessly.</li>
  <li>Built the watch case using resin and CNC-cut glass.</li>
  <li>Programmed the time functions of the watch in C.\n</li>
</ul> 


<b>Design Process</b>
<ul>
  <li>It took me around half a year to design the final PCB and gather all the components I needed for the watch.</li>
  <li>Initially, my watch display consisted of a small oled screen, but I quickly scrapped that idea once I found out about Nixie tubes.</li>
  <li>I had minimal soldering and PCB design experience before making my nixie tube watch, so I learned most of these skills on the go.\n</li>
</ul> 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/IMG_4832.jpg" title="Nixie PCB" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/nixieDiagram.gif" title="Nixie Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/how-glow-discharge-works.png" title="Glow Discharge Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A bit of the watch's innerworkings. On the left is the watch's PCB with all its parts soldered. In the middle is a schematic of a Nixie tube. On the right is a diagram of how glow discharge works (this is what gives Nixie tubes their amber glow).\n
</div>

<b>Coding</b>
<ul>
  <li>I coded the time functions in C.</li>
  <ul>
    <li>I coded on the MPLAB IDE since it has built-in MCU support is easy to use. </li>
    <li>MCUs usually take hex files as code (due to memory space) so I converted my code to hex files.</li>
  </ul> 
  <li>I used a 16 pin-32 pin DIP adapter to connect my PIC-16 MCU to my computer and upload the code to it.</li>
  <ul>
    <li>I worked with a PICkit 3 to transfer files from my computer to the MCU.</li>
  </ul>
</ul> 

<div style="white-space: pre"> 


<p><b>Watch my vid explaining the watch build process and the science behind Nixie tubes!</b></p>
<div style="width: 100%; min-width: 400px; max-width: 800px;">
<div style="position: relative; width: 100%; overflow: hidden; padding-top: 56.25%;">
<p><iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/iHFu8EpVipM" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
</div>
</div>
</div>

<div style="white-space: pre"> 

<p><b><a href="https://github.com/yusiali/nixie-tube-watch">GitHub Repo with documentation and code</a></b></p>
</div> 
