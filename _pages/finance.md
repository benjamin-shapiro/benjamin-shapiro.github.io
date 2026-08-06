---
permalink: /Finance
layout: page
title: Economics & Finance
description: Interactive projects that make game theory easier to explore and reveal arbitrage opportunities hidden in financial networks.
---

<nav class="page-subnav" aria-label="Finance projects">
  <a class="page-subnav__link" href="#nashcalc">NashCalc</a>
  <a class="page-subnav__link" href="#exchange-network">Financial Network Viz</a>
</nav>

<section class="project-section" id="nashcalc">
  <h2 class="project-section__title">NashCalc: Building the Desmos of Game Theory</h2>
  <p>
    NashCalc lays the groundwork for a <a href="https://www.desmos.com">Desmos-style</a>
    learning environment for game theory, turning
    abstract payoff matrices and computational solvers into an interactive visual experience. For
    students early in their learning journey, many existing tools require writing code or interpreting
    results with little visual explanation; NashCalc is designed to lower that barrier. Powered by
    <a href="https://gambitproject.readthedocs.io/en/latest/">Gambit</a> and
    <a href="https://nashpy.readthedocs.io/en/stable/">Nashpy</a>, the current prototype supports
    two-player N &times; N normal-form games.
  </p>

  <img src="/Images/NashCalc1.png" alt="NashCalc title page" loading="lazy" />
  <img src="/Images/NashCalc2.gif" alt="NashCalc functionality recording" loading="lazy" />
</section>

<section class="project-section" id="exchange-network">
  <h2 class="project-section__title">Financial Network Viz</h2>
  <p>
    This visualization uses Python's NetworkX and Matplotlib with the
    <a href="https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm">Bellman-Ford algorithm</a>
    to identify negative cycles in directed graphs of currency pairs, revealing potential arbitrage
    opportunities within and across exchanges.
  </p>

  <img src="/Images/Arbitrage1.jpg" alt="Exchange visualization 1" loading="lazy" />
  <img src="/Images/Arbitrage2.jpg" alt="Exchange visualization 2" loading="lazy" />
  <img src="/Images/Arbitrage3.jpg" alt="Exchange visualization 3" loading="lazy" />
</section>
