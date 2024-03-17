---
layout: page
title: Adaptive Cruise Control
description: 
img: assets/img/ACC_front.jpg
importance: 1
# category: 
# related_publications: true
images:
  compare: true
  slider: true
---

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ACC_1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ACC_2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ACC_3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ACC_4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ACC_5.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

This project involved designing a simple vehicle model with an Adaptive Cruise Control (ACC) system and integrating a haptic steering wheel simulation interface. This cruise control system, if enabled, will have two modes: speed control and position control. If ACC is disabled, the manual driving mode will be active. Additionally, an automatic steering controller using a PID implementation was designed to keep the simulated vehicle on the centerline of the road. High-level design tools MATLAB Simulink and Stateflow was used to make graphic block diagrams and logic flow charts and use code generation to run the code on an NXP processor which interfaced with the haptic motor and the CAN bus.

<div class="row">
    {% include video.liquid path="assets/video/ACC.mp4" class="img-fluid rounded z-depth-1" controls=true %}
</div>
<div class="caption">
    A Final Output Video
</div>
