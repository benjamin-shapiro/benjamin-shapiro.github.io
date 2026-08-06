---
permalink: /AI
layout: page
title: AI
description: Applied AI projects exploring cyclist safety, computer vision, edge computing, mobile development, and real-time audio processing.
---

<nav class="page-subnav" aria-label="AI projects">
  <a class="page-subnav__link" href="#wingman">Wingman</a>
  <a class="page-subnav__link" href="#profanity-filter">Profanity Filter</a>
</nav>

<section class="project-section" id="wingman">
  <h2 class="project-section__title">Wingman: Hazard Detection and Warning System for Cyclists</h2>
  <p>
    Road cyclists need eyes in the back of their heads: traffic can approach quickly from behind while
    a rider's attention stays on the road ahead. <a href="https://www.garmin.com/en-US/p/698001/">Garmin's Varia Radar</a>
    addresses the same problem, but at about $200 it does not distinguish vehicle type or indicate whether
    traffic is approaching from the rider's left, right, or directly behind.
  </p>
  <p>
    Wingman is a computer vision-based second set of eyes for cyclists. At about $10 in materials, the
    prototype is roughly 20x cheaper than Garmin's radar-based alternative. Built from commercial
    off-the-shelf hardware, it uses a rearward-facing camera connected to an
    <a href="https://en.wikipedia.org/wiki/ESP32">ESP32 microcontroller</a> and the processing power
    already in a rider's phone to locate and classify traffic approaching from behind.
  </p>
  <p>
    Garmin's newer <a href="https://www.garmin.com/en-US/p/721258/">$399.99 Varia RCT715</a> adds
    dashcam-style rear-facing recording, a capability Wingman's camera-based design can also provide,
    but at a substantially higher hardware cost.
  </p>
  <p>
    The mobile interface uses <a href="https://kivy.org/">Kivy</a>. A Python edge-computing pipeline uses
    TensorFlow Lite and the <a href="https://arxiv.org/abs/1704.04861">MobileNet model</a> for computer
    vision and classification, then estimates monocular distance with
    <a href="https://xgboost.readthedocs.io/en/stable/">XGBoost</a> using the
    <a href="https://www.cvlibs.net/datasets/kitti/">KITTI Vision Dataset</a> and an approach informed by
    the <a href="https://project.inria.fr/ppniv18/files/2018/10/paper22.pdf">University of Bremen's 2018 DisNet paper</a>.
  </p>

  <img src="/Images/Wingman1.png" alt="Wingman product mockup and poster" loading="lazy" />
  <img src="/Images/Wingman3.gif" alt="Wingman bike, Arduino, and phone render" loading="lazy" />
  <img src="/Images/Wingman2.gif" alt="Wingman Arduino render" loading="lazy" />
</section>

<section class="project-section" id="profanity-filter">
  <h2 class="project-section__title">Real-Time Profanity Filtering in Audio</h2>
  <p>
    Low-latency profanity filter using the Google Cloud Speech-to-Text API with PyAudio and Python
    multiprocessing to manage parallel input and output audio streams.
  </p>

  <img src="/Images/Profanity.png" alt="Profanity filtering icon" loading="lazy" />
</section>
