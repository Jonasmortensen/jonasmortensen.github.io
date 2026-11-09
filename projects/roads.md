---
layout: post
title: 'Road tooling in Unreal Engine'
---

{% include imagenourl.html image="projects/roads/thumbnail.jpg" %}
{% include imagenourl.html image="projects/roads/CobblePath.png" %}
{% include imagenourl.html image="projects/roads/cobbleRoad.png" %}
{% include imagenourl.html image="projects/roads/Path.png" %}

In 2025/2026 I worked at Raw Power Games on their ambitious sandbox war game Chronicles: Medieval. I was part of the procedural generation team more specifically working on terrain and settlement generation. This included building a suite of road tools for artists and designers to control where roads go, and how they look. 

{% include imagenourl.html image="projects/roads/SettlementNetwork.png" %}

In the game the road network is generated procedurally based on a tiered list of points. Designers can decide on a priority for each tier and associate metadata for game mechanics. The tool will then use pathfinding with heuristics to build an optimal road network that considers the flow of the terrain. 

{% include imagenourl.html image="projects/roads/EuropeNetwork.png" %}

We used the pathfinding system in both the settlements and the "overworld map" which shows a miniature version of Europe. 

{% include imagenourl.html image="projects/roads/SteepRoadEM.png" %}

The heuristics make sure that the pathfinding tries to find the least steep path up the mountain. It then flattens the terrain across the road before rendering its surface.
