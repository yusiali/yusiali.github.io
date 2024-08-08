---
layout: page
title: MNIST Neural Network from Scratch
description: A neural network that recognizes handwritten digits with 98% precision
img: assets/img/mnist.gif
importance: 2
category: work
related_publications: true
giscus_comments: false
---


<b>Objective: Build a neural network from scratch for the MNIST database.</b>
<ul>
  <li>Built from scratch with numpy</li>
  <li>Optimized neural network with 98% precision after 20 epochs of training</li>
  <li>Major changes from v1: </li>
  <ul>
    <li>Switched from batch gradient descent to mini-batch gradient descent</li>
    <li>Added momentum to descent algo</li>
    <li>Better initialization of weights</li>
  </ul>
  <br>
  <br>
</ul> 

<div class="row justify-content-sm-center">
    <div class="col-5 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mnistDigits.png" title="mnist digits" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-7 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mnistnet.png" title="mnist neural net diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample digits from the MNIST database (left) and a simple visual of how the neural network trains on them (right).
  <br>
  <br>
</div>


{% cite mnistAli %} contains python code for both v1 and v2 of the neural network. 
  <br>
  <br>

<b>Helpful Resources</b>
<ul>
  <li><a href="https://www.codecademy.com/courses/intro-to-deep-learning-with-tensor-flow/">Codecademy's courses on deep learning and neural networks</a></li>
  <li>Official page for MNIST database {% cite mnistData %}</li>
  <li>Johnathan Weisberg's blogs on neural networks {% cite mnistWeisberg %}</li>
</ul> 
  <br>
  <br>
  <br>
  <br>
