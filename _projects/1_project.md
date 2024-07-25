---
layout: page
title: Nixie Tube Watch
description: DIY watch with Nixie tubes from the 1950s. 
img: assets/img/NixieTubeVideoThumbnail.png
importance: 1
category: work
related_publications: true
---

<b>Objective: Build an analog watch from scratch using cathode ray Nixie tubes from the 1950s.</b>
<ul>
  <li>Designed printed circuit boards to keep the form factor of the watch as compact as possible.</li>
  <li>Created a Qi standard charging module for the watch to charge wirelessly.</li>
  <li>Built the watch case using resin and CNC-cut glass.</li>
  <li>Programmed the time functions of the watch in C.</li>
</ul> 


<b>Design Process</b>
<ul>
  <li>It took me around half a year to design the final PCB and gather all the components I needed for the watch.</li>
  <li>Initially, my watch display consisted of a small oled screen, but I quickly scrapped that idea once I found out about Nixie tubes.</li>
  <li>I had minimal soldering and PCB design experience before making my nixie tube watch, so I learned most of these skills on the go lol.</li>
</ul> 


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


<b>Watch my vid explaining the watch build process and the science behind Nixie tubes!</b>
<iframe width="640" height="338" src="https://www.youtube.com/embed/iHFu8EpVipM" title="How I Made A Nixie Tube Watch!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



<b><a href="https://github.com/yusiali/nixie-tube-watch">GitHub Repo with documentation and code</a></b>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
