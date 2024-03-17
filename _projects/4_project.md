---
layout: page
title: Active Control of a Vehicle Anti-Roll Bar
description: 
img: assets/img/ARB/ARB.jpg
importance: 3
# category: 
images:
  compare: true
  slider: true
---

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_5.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_6.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_7.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_8.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/ARB/ARB_9.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

This project presents a successful implementation of PID controller for a pneumatically actuated active roll control suspension system. A full vehicle model which consists of ride, handling and tire subsystems to study vehicle dynamics behavior in lateral direction is derived. An active roll control (ARC) suspension system is then developed on the full vehicle model to reduce unwanted vehicle motions during cornering maneuvers such as body roll angle, body roll rate, vertical acceleration of the body and body heave. The proposed controller structure for the ARC system is PID control with roll moment rejection loop. The results of the project shows that the proposed control structure is able to significantly improve the dynamics performance of the vehicle during step steer maneuver compared to a passive vehicle system. It can also be noted that the additional roll moment rejection loop is able to further improve the performance of the PID controller for the ARC system.
