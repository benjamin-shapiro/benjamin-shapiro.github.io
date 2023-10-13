---
permalink: /AI
layout: page
title: AI & Computer Vision
---

* ### Wingman: Hazard Detection and Warning System for Cyclists 
  >A low-cost computer vision-based real-time hazard detection system for cyclists, empowering riders with enhanced situational awareness at 10% of the cost of leading LIDAR solutions. Uses [Kivy](https://kivy.org/) (mobile app GUI), the Arduino [ESP32-CAM](https://loboris.eu/ESP32/ESP32-CAM%20Product%20Specification.pdf) microcontroller (for rearward-facing video acquisition sent over wifi to the mobile device), a Python ML backend for object detection and classification using TensorFlow Lite and the [MobileNet vision model](https://arxiv.org/abs/1704.04861) plus a custom monocular distance estimation model trained using the [KITTI Vision Dataset](https://www.cvlibs.net/datasets/kitti/) via [XGBoost](https://xgboost.readthedocs.io/en/stable/) using an implementation from the [DisNet 2018 Paper](https://project.inria.fr/ppniv18/files/2018/10/paper22.pdf).

![Wingman Product Mockup and Poster](/Images/Wingman1.png)

![Wingman Arduino Render](/Images/Wingman2.gif)

![Wingman Bike, Arduino, and Phone Render](/Images/Wingman3.gif)

* ### Real-Time Profanity Filtering in Audio
  >Low-latency profanity filter that uses the Google Cloud Speech-to-Text API with PyAudio and Python multiprocessing.