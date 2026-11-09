---
layout: post
title: 'Procedural Planet'
---

{% include imagenourl.html image="projects/planet/thumbnail.jpg" %}

This personal project is an experiment with a new data model for procedural planets.

{% include imagenourl.html image="projects/planet/Orbit.png" %}

{% include imagenourl.html image="projects/planet/View3.png" %}

Playing games like *No Man's Sky* I was always distracted by the obvious reliance on procedural noises and often thought it yielded uninteresting results. On the contrary I was always impressed with the artistic control that algorithms like Wave Function Collapse (WFC) provide for procedural generation.

{% include imagenourl.html image="projects/planet/DataCoarse.png" %}

So my idea was to generate huge organic worlds based on data from a wave function collapse solution on an irregular grid wrapped around a planet.

{% include imagenourl.html image="projects/planet/DataFinest.png" %}

As the camera moves closer to the surface, the WFC grid is subdivided allowing for finer details. This debug view shows the weights driving the landscape height data.

The actual height data is coming from prebaked terrain maps that are also distributed using a WFC solver.

Rendering features on the planet project:
- CPU-side mesh generation using Unity Burst-compiled jobs
- Water rendering with Gerstner waves supporting refraction and Screen Space Reflections
- Volumetric cloud rendering
- Realistic atmosphere

{% include imagenourl.html image="projects/planet/Beach.png" %}

{% include imagenourl.html image="projects/planet/Clouds.png" %}

{% include imagenourl.html image="projects/planet/Cloudy.png" %}

{% include imagenourl.html image="projects/planet/Ocean.png" %}

{% include imagenourl.html image="projects/planet/View2.png" %}
