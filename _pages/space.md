---
permalink: /Space
layout: page
title: Space
---

* ### EO Unlocked: Metadata Search Engine for Earth Observation
  
> User-centric innovation for Earth Observation, seeking to increase market transparency through “big metadata” analysis. Uses space situational awareness data from [Celestrak](https://celestrak.org/), propagated via [SGP4](https://en.wikipedia.org/wiki/Simplified_perturbations_models), and made searchable using an [R-Tree spatial index](https://en.wikipedia.org/wiki/R-tree). Search and filtering GUI developed in React and ThreeJS with the use of [Open-Meteo API](https://open-meteo.com/) for supplemental weather data. Sensor specifications for thousands of spacecraft mined from [ESA's eoPortal](https://www.eoportal.org/), [the World Meteorological Organization's "Oscar" Tool](https://space.oscar.wmo.int/), [Nanosats EU](https://www.nanosats.eu/), and [Gunter's Space Page](https://space.skyrocket.de/index.html). The unstructured data was then synthesized and organized programmatically using the [OpenAI API](https://openai.com/blog/openai-api). 

![EO Unlocked Gif Representing Proliferation of Spacecraft](/Images/EOUnlocked1.gif)

>Simply select a location and historical timeframe of interest and receive instant results for predicted visual footprints of a virtual constellation of more than 350 spacecraft, ranked by cloud coverage. 

![Search Result from EO Unlocked given a lat,lon as well as a timeframe of interest](/Images/EOUnlocked2.png)

* ### Light sail deployment simulation

>Simulation of on-orbit free-flying light sail deployment from the [Cornell Alpha CubeSat](https://alphacubesat.cornell.edu/index.html), developed and choreographed in Unreal Engine 4. Alpha will carry the world’s first retroreflective, solo-flying light sail—and become the trailblazer for future missions to our nearest stellar neighbor, Alpha Centauri.
  
<a href="https://youtu.be/bK_9kRmw0oA" target="_blank">
  <img src="/Images/AlphaAnim1.gif" alt="Alpha Animation 1" />
</a>

<a href="https://youtu.be/mtEorwJlq1c" target="_blank">
  <img src="/Images/AlphaAnim2.gif" alt="Alpha Animation 2" />
</a>

<a href="https://youtu.be/5sR2MDufFdQ" target="_blank">
  <img src="/Images/AlphaAnim3.gif" alt="Alpha Animation 3" />
</a>

* ### Detecting Cloud Cover from Space Using Infrared Sensors (Miami Young Data Scientists)

>We had the opportunity to run our code on-orbit aboard Spire Global's Lemur 2 NanoSatellite as part of a winning experimental machine learning entry in the 2015 Association of Space Explorers (ASE) Astrosat Challenge. 

<a>
  <img src="/Images/ArdusatSat.png" width="699" alt="Render of Ardusat NanoSat" />
</a>

![Winner Announcement: ASE Astrosat Challenge](/Images/ArdusatWinner.png)

>Data collection was constrained to 15 kilobytes, approximately 1500 observations, from an equatorial orbit. Used a support vector machine approach on infrared emissivity data to predict cloud cover, validated with live weather apis. 

![Experimental Code: Detecting Cloud Cover from Space Using Infrared Sensors](/Images/ArdusatCode.png)

>Achieved approximately 75% accuracy in the binary classification problem (is it a cloud or not?). 

<a>
  <img src="/Images/Countdown.png" width="350" height="350" alt="Countdown Institute Logo">
</a>
<a>
  <img src="/Images/ArdusatLinReg.png" width="350" height="350" alt="Data Output with Linear Regression Best Fit">
</a>

>My teammate and I delivered our findings to the local Miami tech community with the Countdown Institute and taught introductory space and data science to local students.

![Ardusat Space Kit](/Images/Ardusat.jpg)