---
layout: page
title: Autonomous Racing Vehicle
description: 
img: assets/img/AR/AR.jpg
importance: 2
# category: 
# giscus_comments: true
images:
  compare: true
  slider: true
---

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_5.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_6.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_7.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

The project focused on automating a rear-wheel-drive, front-wheel-steer bicycle model Formula One car using MATLAB. A race line tracking feedback controller was developed to compute the corrective steering angle dynamically by evaluating the deviation of the car’s position from the predefined race line. Additionally, a velocity controller was designed, incorporating constraints on driving and lateral forces, aiming to optimize lap times. This comprehensive approach resulted in achieving an optimized lap time of 171.75 seconds specifically tailored for the Circuit of America track, demonstrating the effectiveness of the controllers in enhancing racing performance.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_8.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_9.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR/AR_10.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

<div class="row">
    {% include video.liquid path="assets/video/AR.mp4" class="img-fluid rounded z-depth-1" controls=true %}
</div>
<div class="caption">
    A Final Output Video
</div>