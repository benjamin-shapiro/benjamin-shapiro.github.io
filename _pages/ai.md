---
permalink: /AI
layout: page
title: AI
---

<nav class="page-subnav" aria-label="AI projects">
  <a class="page-subnav__link" href="#wingman">Wingman</a>
  <a class="page-subnav__link" href="#profanity-filter">Profanity Filter</a>
</nav>

<section class="project-section" id="wingman">
  <h2 class="project-section__title">Wingman: Hazard Detection and Warning System for Cyclists</h2>
  <p>
    A low-cost hazard detection system for cyclists, designed to improve situational awareness
    without the cost of lidar-heavy hardware. Uses <a href="https://kivy.org/">Kivy</a> for the
    mobile app GUI, Arduino-based sensing hardware for rearward video acquisition, and a Python
    edge-computing pipeline for computer vision, classification, and monocular distance estimation
    using TensorFlow Lite, the <a href="https://arxiv.org/abs/1704.04861">MobileNet vision model</a>,
    the <a href="https://www.cvlibs.net/datasets/kitti/">KITTI Vision Dataset</a>, and
    <a href="https://xgboost.readthedocs.io/en/stable/">XGBoost</a> via an implementation from the
    <a href="https://project.inria.fr/ppniv18/files/2018/10/paper22.pdf">DisNet 2018 paper</a>.
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
