---
permalink: /Space
layout: page
title: Space
---

<nav class="page-subnav" aria-label="Space projects">
  <a class="page-subnav__link" href="#light-sail">LightSail</a>
  <a class="page-subnav__link" href="#cloud-cover">Cloud Cover Detection</a>
</nav>

<section class="project-section" id="light-sail">
  <h2 class="project-section__title">LightSail Deployment Sim</h2>
  <p>
    Simulation of on-orbit free-flying light sail deployment from the
    <a href="https://alphacubesat.cornell.edu/index.html">Cornell Alpha CubeSat</a>, developed and
    choreographed in Unreal Engine 4. Alpha was deployed from the ISS via Nanoracks in late 2025,
    carrying the world's first retroreflective, free-flying light sail and becoming a trailblazer
    for future missions to our nearest stellar neighbor, Alpha Centauri. Alpha concluded mission
    ops in early 2026, with a follow-on in the pipeline at the
    <a href="https://www.spacecraftresearch.com">Space Systems Design Studio</a>.
  </p>

  <a href="https://youtu.be/5sR2MDufFdQ" target="_blank" rel="noopener noreferrer">
    <img src="/Images/AlphaAnim3.gif" alt="Alpha animation 3" loading="lazy" />
  </a>

  <a href="https://youtu.be/bK_9kRmw0oA" target="_blank" rel="noopener noreferrer">
    <img src="/Images/AlphaAnim1.gif" alt="Alpha animation 1" loading="lazy" />
  </a>

  <a href="https://youtu.be/mtEorwJlq1c" target="_blank" rel="noopener noreferrer">
    <img src="/Images/AlphaAnim2.gif" alt="Alpha animation 2" loading="lazy" />
  </a>
</section>

<section class="project-section" id="cloud-cover">
  <h2 class="project-section__title">Detecting Cloud Cover from Space Using Infrared Sensors (Miami Young Data Scientists)</h2>
  <p>
    We had the opportunity to run our code on-orbit aboard Spire Global's Lemur 2 NanoSatellite as
    part of a winning experimental machine learning entry in the 2015 Association of Space
    Explorers (ASE) Astrosat Challenge.
  </p>

  <img src="/Images/ArdusatSat.png" alt="Render of Ardusat nanosatellite" loading="lazy" />
  <img src="/Images/ArdusatWinner.png" alt="Winner announcement for the ASE Astrosat Challenge" loading="lazy" />

  <p>
    Data collection was constrained to 15 kilobytes, approximately 1500 observations, from an
    equatorial orbit. Used a support vector machine approach on infrared emissivity data to predict
    cloud cover, validated with live weather APIs.
  </p>

  <img src="/Images/ArdusatCode.png" alt="Experimental code for detecting cloud cover from space using infrared sensors" loading="lazy" />

  <p>
    Achieved approximately 75% accuracy in the binary classification problem (is it a cloud or
    not?).
  </p>

  <div class="project-image-row">
    <img src="/Images/Countdown.png" alt="Countdown Institute logo" loading="lazy" />
    <img src="/Images/ArdusatLinReg.png" alt="Data output with linear regression best fit" loading="lazy" />
  </div>

  <p>
    My teammate and I delivered our findings to the local Miami tech community with the Countdown
    Institute and taught introductory space and data science to local students.
  </p>

  <img src="/Images/Ardusat.jpg" alt="Ardusat space kit" loading="lazy" />
</section>
