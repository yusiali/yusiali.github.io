---
layout: page
title: AggiesBCI
description: A brain-controlled wheelchair that converts thoughts to real-world movement
img: assets/img/AggiesBCILogo.png
importance: 1
category: fun
related_publications: true
---

<div class="row justify-content-center">    <div class="mt-3 mt-md-0 " style="width: 70%;">
        {% include figure.liquid loading="eager" path="assets/img/AggiesBCITeam.JPG" title="Nixie Watch" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The AggiesBCI Team: (Pranav, Garner, Tejas, Oswin, me, & Daniel). None of this would have been possible without you guys!
<br>
<br>
<br>
</div>

<b>Objective: Develop a brain-computer interface system that enables wheelchair control using thoughts as command inputs.</b>
<ul>
  <li>Disassembled an e-wheelchair controller and soldered its test points to an Arduino Nano.</li>
  <li>Trained mental commands using an EMOTIV Insight headset and converted them into movement inputs.</li>
  <li>Presented our prototype at the Aggies Create Innovation Expo and placed 1st out of 20 teams! </li>
  <li>Currently transitioning to testing this product with prospective users.</li>
  <br>
</ul> 

<br>
<br>
<b>Our Innovation Expo Presentation</b>
<div class="row justify-content-center">
<iframe src="https://1drv.ms/p/c/ce8588b966e5e6f5/IQTctm6FmkamSrHcnPeA2CrBAa59I_Fd3RgVNvGW-F_JH6c?wdAr=1.7777777777777777" width="876px" height="518px" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
<div>
<br>
<br>
<br>
<br>


<div class="row">
    <div class="col-sm-3 mt-3 mt-md-0" style="width: 25%;">
        {% include figure.liquid loading="eager" path="/assets/img/IMG_5930.gif" title="Nixie PCB" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/WorkPic.JPG" title="Nixie Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wheelchair.JPG" title="Glow Discharge Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A bit of the project's innerworkings. On the left is our linear actuator system in action. In the middle is our initial BCI protype using an OpenBCI Ganglion board. On the right is our system housed onto our wheelchair.


</div>
<br>
<br>
<b>Coding</b>
<ul>
  <li>Hacking the Hexbug</li>
  <ul>
    <li>I coded the Hexbug controls using Arduino C.</li>
    <li>I used Python and the BrainFlow library to communicate with the OpenBCI Ganglion board and detect neuromuscular commands.</li>
    <li>I sent all BCI commands through the serial monitor to an Arduino Uno connected to the Hexbug controller.</li>
  </ul> 
  <li>BCI-controlled Wheelchair</li>
  <ul>
    <li>I worked with the EMOTIV Insight headset to train the mental commands using the EmotivBCI software.</li>
  </ul>
    <ul>
    <li>I coded in Python using the Cortex API to detect the headset's commands and sent them to the Arduino Nano via the serial monitor.</li>
  </ul>
  <ul>
    <li>I used C to code the servo movements for the linear actuator and take in BCI commands through the serial monitor.</li>
  </ul>
  <li>{% cite AggiesBCIRepo %} contains additional EMOTIV/OpenBCI documentation and all the code I developed for this project.</li>
</ul> 
<br>
<br>

<b>What's Next</b>
<ul>
  <li>Refining our Design</li>
  <ul>
    <li>This upcoming semester, our team will work on reinforcing our wheelchair interface and perhaps hacking the joystick directly as we did with the Hexbug controller.</li>
    <li>We also aim to make our design more modular to fit various wheelchair models.</li>
  </ul> 
  <li>Future Project Ideas</li>
  <ul>
    <li>A BCI system enabling control of digital interface through mental commands (mouse, cursor, keyboard, etc.). This would give individuals with mobility issues much more freedom in today's world.</li>
  </ul>
    <ul>
    <li>A mechanical arm that can grasp/move items based on mental commands. This would essentially be a 'third arm' for indivuduals working in environments that require their limbs to be occupied (construction, mechanical engineering, etc.).</li>
  </ul>
</ul> 
<br>
<br>




