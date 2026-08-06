---
permalink: /Geo
layout: page
title: Geospatial
description: Geospatial projects exploring Earth observation, Los Angeles mobility, environmental risk, and the unexpected ways data can reveal a place.
---

<nav class="page-subnav" aria-label="Geospatial projects">
  <a class="page-subnav__link" href="#eo-unlocked">EO Unlocked</a>
  <a class="page-subnav__link" href="#time-space-cartogram">Time-Space LA</a>
  <a class="page-subnav__link" href="#toxic-waste">Toxic Waste</a>
  <a class="page-subnav__link" href="#wildfire-insurance">Wildfire + Insurance</a>
  <a class="page-subnav__link" href="#sea-level-rise">Sea Level Rise</a>
  <a class="page-subnav__link" href="#aromap">Aromap</a>
</nav>

<section class="project-section" id="eo-unlocked">
  <h2 class="project-section__title">EO Unlocked: Metadata Search Engine for Earth Observation</h2>
  <a class="live-demo-link ui-label" href="https://eo-unlocked.onrender.com" target="_blank" rel="noopener noreferrer">Live demo</a>
  <p>
    EO Unlocked is a user-centric Earth observation discovery interface for modeling virtual
    constellations and past, present, and future opportunities for coordination across
    commercial and civil assets. Inspired by Cory Doctorow's writing on
    <a href="https://www.eff.org/deeplinks/2019/10/adversarial-interoperability">adversarial interoperability</a>,
    it synthesizes public metadata into a system-level view without requiring direct integration with
    individual satellite operators or their APIs. Essentially, it is Google Flights for Earth
    observation: who can see what and when.
  </p>
  <p>
    It uses space situational awareness data from <a href="https://celestrak.org/">CelesTrak</a> to
    propagate satellite orbits with <a href="https://en.wikipedia.org/wiki/Simplified_perturbations_models">SGP4</a>,
    then makes predicted observation footprints searchable through spatial computation with an
    <a href="https://en.wikipedia.org/wiki/R-tree">R-Tree index</a>. A React and ThreeJS-based GUI enables
    search and filtering of results. It also incorporates supplemental weather data from the
    <a href="https://open-meteo.com/">Open-Meteo API</a>, since cloud cover can influence access opportunities.
  </p>
  <p>
    Sensor specifications for thousands of spacecraft were mined from
    <a href="https://www.eoportal.org/">ESA's eoPortal</a>,
    <a href="https://space.oscar.wmo.int/">the World Meteorological Organization's Oscar tool</a>,
    <a href="https://www.nanosats.eu/">Nanosats EU</a>, and
    <a href="https://space.skyrocket.de/index.html">Gunter's Space Page</a>. The unstructured data
    was then synthesized and organized programmatically using the
    <a href="https://openai.com/blog/openai-api">OpenAI API</a>.
  </p>

  <img src="/Images/EOUnlocked1.gif" alt="EO Unlocked gif representing proliferation of spacecraft" loading="lazy" />

  <p>
    Simply select a location and historical timeframe of interest and receive instant results for
    predicted visual footprints of a virtual constellation of more than 350 spacecraft, ranked by
    cloud coverage.
  </p>

  <img src="/Images/EOUnlocked2.png" alt="Search result from EO Unlocked given a latitude, longitude, and timeframe of interest" loading="lazy" />
</section>

<section class="project-section" id="time-space-cartogram">
  <h2 class="project-section__title">Los Angeles Freeway Time-Space Cartogram</h2>
  <a class="live-demo-link ui-label" href="/Geo/time-space-cartogram/">Open interactive cartogram</a>
  <p>
    In Los Angeles, distance is measured as much in minutes as in miles: a ten-mile trip can take
    ten minutes or an hour, depending on the time of day. This interactive experiment redraws the
    city according to freeway travel time rather than geographic distance. Roughly 200 freeway-served
    catchments expand and contract across a typical weekday using five-minute median speeds from 207
    Caltrans PeMS sensors in the historical METR-LA dataset.
  </p>
  <img
    class="cartogram-preview"
    src="/Images/TimeSpaceCartogramLongBeachHex.gif"
    width="840"
    height="720"
    alt="Animated Los Angeles freeway time-space cartogram from the Near Long Beach · 008 origin, with color-changing hexagonal catchments, warped traffic-colored freeways, and travel times beside major cities across a typical weekday"
    loading="lazy"
    decoding="async"
  />
</section>

<section class="project-section" id="toxic-waste">
  <h2 class="project-section__title">2022 LA County Toxic Waste Release Hazard to K-12 Educational Institutions: A Geospatial Analysis</h2>
  <p>
    This analysis maps 2022 Toxic Release Inventory (TRI) facilities near K-12 schools in Los Angeles
    County to identify areas of potential exposure concern using spatial buffers and overlays. Of the
    TRI sites analyzed, 92.9% were within one mile of a school, and 64 schools were near multiple
    high-emissions facilities.
  </p>

  <img src="/Images/ToxicWaste1.png" alt="LA TRI facilities overlaid over areas within one mile of a school" loading="lazy" />
  <p class="project-caption">LA TRI facilities overlaid over areas within one mile of a school.</p>

  <img src="/Images/ToxicWaste2.png" alt="Significant large TRI emissions site count in proximity to schools with Torrance highlighted" loading="lazy" />
  <p class="project-caption">Significant large TRI emissions site count in proximity to schools, with Torrance highlighted.</p>
</section>

<section class="project-section" id="wildfire-insurance">
  <h2 class="project-section__title">California Wildfire Hazard and Insurance Stress Dashboard</h2>
  <p>
    Wildfire risk is reshaping California's housing and insurance markets, but the physical and financial
    sides of the problem are rarely viewed together. Built in ArcGIS Experience Builder, this dashboard
    combines wildfire hazard and insurance stress indicators in interactive maps and charts to show where
    those pressures overlap.
  </p>
  <iframe width="800" height="800" frameborder="0" allowfullscreen src="https://arcg.is/0Hyif4" title="California Wildfire Hazard and Insurance Stress Dashboard"></iframe>
</section>

<section class="project-section" id="sea-level-rise">
  <h2 class="project-section__title">Rising Sea Level Risks to Miami (2100 Inundation Projections)</h2>
  <p>
    This analysis maps potential 2100 inundation across Miami using NASA and Florida Climate Center
    projections applied to a digital elevation model. The results highlight low-lying neighborhoods
    and infrastructure that become increasingly vulnerable during storm surge and high-tide events.
  </p>

  <img src="/Images/SeaLevelRise.png" alt="Sea level rise map for Miami using a digital elevation model" loading="lazy" />
</section>

<section class="project-section" id="aromap">
  <h2 class="project-section__title">Aromap: The Olfactory Social Network</h2>
  <p>
    Track smells around your area. Smell something stinky? Report it! Smell something
    heavenly and want others to experience it? Enlighten your friends. In a world where smells are
    our most dear sense, Aromap is your guiding light.
  </p>

  <img src="/Images/Aromap1.png" alt="Aromap screenshot 1" loading="lazy" />
  <img src="/Images/Aromap2.png" alt="Aromap screenshot showing the smell submission flow" loading="lazy" />
</section>
