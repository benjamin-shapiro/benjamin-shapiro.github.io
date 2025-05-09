---
permalink: /Geo
layout: page
title: Maps & Geospatial
---

* ### EO Unlocked: Metadata Search Engine for Earth Observation
  
> User-centric innovation for Earth Observation, seeking to increase market transparency through “big metadata” analysis. Uses space situational awareness data from [Celestrak](https://celestrak.org/), propagated via [SGP4](https://en.wikipedia.org/wiki/Simplified_perturbations_models), and made searchable using an [R-Tree spatial index](https://en.wikipedia.org/wiki/R-tree). Search and filtering GUI developed in React and ThreeJS with the use of [Open-Meteo API](https://open-meteo.com/) for supplemental weather data. Sensor specifications for thousands of spacecraft mined from [ESA's eoPortal](https://www.eoportal.org/), [the World Meteorological Organization's "Oscar" Tool](https://space.oscar.wmo.int/), [Nanosats EU](https://www.nanosats.eu/), and [Gunter's Space Page](https://space.skyrocket.de/index.html). The unstructured data was then synthesized and organized programmatically using the [OpenAI API](https://openai.com/blog/openai-api). 

![EO Unlocked Gif Representing Proliferation of Spacecraft](/Images/EOUnlocked1.gif)

>Simply select a location and historical timeframe of interest and receive instant results for predicted visual footprints of a virtual constellation of more than 350 spacecraft, ranked by cloud coverage. 

![Search Result from EO Unlocked given a lat,lon as well as a timeframe of interest](/Images/EOUnlocked2.png)

* ### 2022 LA County Toxic Waste Release Hazard to K-12 Educational Institutions: A Geospatial Analysis
  
>Assessing the proximity of Toxic Release Inventory (TRI) facilities to K-12 schools in Los Angeles County, identifying significant potential exposure risks for students through utilization of spatial buffering and overlay tools. Results indicate that 92.9% of TRI sites are located within one mile of a school, with 64 schools situated near multiple high-risk facilities. 

![LA TRI Facilities Overlayed over Areas within One Mile of a School](/Images/ToxicWaste1.png)
>Above: LA TRI Facilities Overlayed over Areas within One Mile of a School

>Below: Significant Large TRI Emissions Site Count in Proximity to Schools (Torrance Highlight)

![Significant Large TRI Emissions Site Count in Proximity to Schools (Torrance Highlight)](/Images/ToxicWaste2.png)

* ### Rising Sea Level Risks to Miami (2100 Inundation Projections)
>Highlighting severe inundation risks to densely populated and economically vital areas in the city using projections from NASA and the Florida Climate Center. The results, derived from map algebra operations performed on a digital elevation model, visually emphasize increased vulnerability along low-lying coastal regions, particularly during storm surges and high-tide events, underscoring the urgent need for substantial mitigation efforts to protect Miami’s infrastructure and residents.

![Sea Level Rise Map for Miami Utilizing DEM](/Images/SeaLevelRise.png)

* ### Aromap: The Olfactory Social Network

>Track and report smells around your area! Smell something stinky? Report it! Smell something heavenly and want others to experience it? Enlighten your friends! In a world where smells are our most dear sense, aroMap is your guiding light.

![Aromap Screenshot 1](/Images/Aromap1.png)

![Aromap Screenshot 2 (adding a smell)](/Images/Aromap2.png)

* ### Yosemite National Park Map Replication and Enhancement
  
> Effort to reproduce and then enhance the symbology of Yosemite National Park's official map by highlighting iconic natural landmarks -- including mountain peaks, waterfalls, and granite domes -- previously understated due to generic and ambiguous representations. New icons and labeling schemes were introduced to emphasize the unique prominence of these features, improving map clarity, visitor orientation, and engagement with the park's landscape.
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script><!-- Add custom element to <body> of your page --> <arcgis-embedded-map style="height:600px;width:700px;" item-id="ac23f352324f4eb7980c0ae88f2c9f35" theme="light" legend-enabled portal-url="https://uclageography.maps.arcgis.com" ></arcgis-embedded-map>
