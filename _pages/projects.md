---
layout: default
title: Projects
---

# Projects

* ### EO Unlocked: Metadata Search Engine for Earth Observation
  > User-centric innovation for Earth Observation, seeking to increase market transparency through “big metadata” analysis. Uses space situational awareness data from [Celestrak](https://celestrak.org/), propagated via [SGP4](https://en.wikipedia.org/wiki/Simplified_perturbations_models), and made searchable using an [R-Tree spatial index](https://en.wikipedia.org/wiki/R-tree). Search and filtering GUI developed in React and ThreeJS with the use of [Open-Meteo API](https://open-meteo.com/) for supplemental weather data. Sensor specifications for thousands of spacecraft mined from [ESA's eoPortal](https://www.eoportal.org/), [the World Meteorological Organization's "Oscar" Tool](https://space.oscar.wmo.int/), [Nanosats EU](https://www.nanosats.eu/), and [Gunter's Space Page](https://space.skyrocket.de/index.html). The unstructured data was then synthesized and organized programmatically using the [OpenAI API](https://openai.com/blog/openai-api). 
  
  ![EO Unlocked Gif Representing Proliferation of Spacecraft](/Images/EOUnlocked1.gif)

  >Simply select a location and historical timeframe of interest and receive instant results for predicted visual footprints of a virtual constellation of more than 350 spacecraft, ranked by cloud coverage. 
  
  ![Search Result from EO Unlocked given a lat,lon as well as a timeframe of interest](/Images/EOUnlocked2.png)
  
* ### Wingman: Hazard Detection and Warning System for Cyclists 
  >A low-cost computer vision-based real-time hazard detection system for cyclists, empowering riders with enhanced situational awareness at 10% of the cost of leading LIDAR solutions. Uses [Kivy](https://kivy.org/) (mobile app GUI), the Arduino [ESP32-CAM](https://loboris.eu/ESP32/ESP32-CAM%20Product%20Specification.pdf) microcontroller (for rearward-facing video acquisition sent over wifi to the mobile device), a Python ML backend for object detection and classification using TensorFlow Lite and the [MobileNet vision model](https://arxiv.org/abs/1704.04861) plus a custom monocular distance estimation model trained using the [KITTI Vision Dataset](https://www.cvlibs.net/datasets/kitti/) via [XGBoost](https://xgboost.readthedocs.io/en/stable/) using an implementation from the [DisNet 2018 Paper](https://project.inria.fr/ppniv18/files/2018/10/paper22.pdf).

![Wingman Product Mockup and Poster](/Images/Wingman1.png)

![Wingman Arduino Render](/Images/Wingman2.gif)

![Wingman Bike, Arduino, and Phone Render](/Images/Wingman3.gif)

* ### NashCalc: The Most Intuitive Way to Game Theorize
  >An intuitive interface designed to improve accessibility to and interactivity with algorithmic game theory libraries like [Gambit](http://www.gambit-project.org/gambit13/pyapi.html) and [Nashpy](https://nashpy.readthedocs.io/en/stable/) through modern web frameworks, reducing the field’s barriers to entry for students and researchers alike. Currently functional for two-player standard form games of NxN dimensions. 
  
  ![NashCalc Title Page](/Images/NashCalc1.png)

  ![NashCalc Functionality Recording](/Images/NashCalc2.gif)
  
* ### Aromap: The Olfactory Social Network
  >Track and report smells around your area! Smell something stinky? Report it! Smell something heavenly and want others to experience it? Enlighten your friends! In a world where smells are our most dear sense, aroMap is your guiding light.

  ![Aromap Screenshot 1](/Images/Aromap1.png)

  ![Aromap Screenshot 2 (adding a smell)](/Images/Aromap2.png)

* ### Financial Exchange Network Visualization and Analysis
  >Visualization generated with Python's NetworkX and Matplotlib using the [Bellman-Ford algorithm](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm) to identify negative cycles in the bidirected graphs of currency pairs.

  ![Exchange Visualization](/Images/Arbitrage1.jpg)
  
  ![Exchange Visualization](/Images/Arbitrage2.jpg)
  
  ![Exchange Visualization](/Images/Arbitrage3.jpg)

* ### Real-Time Profanity Filtering in Audio
  >Low-latency profanity filter that uses the Google Cloud Speech-to-Text API with PyAudio and Python multiprocessing.
  