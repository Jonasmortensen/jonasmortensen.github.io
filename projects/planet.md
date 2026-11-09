---
layout: post
title: 'Procedural Planet'
---

{% include imagenourl.html image="projects/planet/thumbnail.jpg" %}

This personal project is an expriment with a new data model for procedural planets.

 Playing games like *No Mans Sky* I was always distracted by the ovbious reliance on procedural noises and often thought it yielded uninteresting results. On the contrary I was always impressed with the artistic control that algorithms like Wave Function Collapse (WFC) provide for procedural generation. So my idea was to generate huge organic worlds based on data from a wave function collapse solution on a grid that is subdivided based on camera distance.

 In the animation below you can see how the WFC solver is used to generate the coastline of the landmasses on the planet. 

The actual height data is coming from prebaked terrain maps that are also distributed with a WFC solver. 

Rendering features on the planet project:
- CPU Side mesh generation using the Unity Burst compiled Jobs
- Water rendering with gerstner waves supporting refraction and Screen Space Reflections
- Volumetric Cloud Rendering
- Realistic atmosphere

