---
layout: post
title: 'Procedural Terrain'
---

{% include imagenourl.html image="projects/terrain/thumbnail.jpg" %}

The terrain authoring tools inside Unity are not great. This project was an exploration of a workflow where a terrain is authored completely within Houdini and then exported and converted to the Unity Terrain Data format.

{% include imagenourl.html image="projects/terrain/top.png" %}
The terrain also uses a custom shader to provide some more interesting lighting. 

{% include imagenourl.html image="projects/terrain/splat.png" %}
I use Houdini to render splat maps based on slope, flow, height, ambient occlusion etc.

{% include imagenourl.html image="projects/terrain/grass.png" %}
Houdini also generates density maps for grass procedurally. 
