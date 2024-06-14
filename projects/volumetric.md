---
layout: post
title: 'Volumetric Lighting'
---

<style>
.video-holder {
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.25%;
  overflow: hidden;
}
.video-holder iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
<div class="video-holder">
  <iframe
    id="existing-iframe-example"
    width="640" height="360"
    src="https://www.youtube.com/embed/IWIo7gMPCPA?playlist=IWIo7gMPCPA&autoplay=1&mute=1&enablejsapi=1&controls=0&loop=1"
    frameborder="0"
></iframe>
</div>

This scene was built to showcase a volumetric lighting system I made for the Universal Render Pipeline in Unity. The volumetric lighting works by rendering particles in to a 3D texture and then ray marching that while sampling shadow maps (Technique described by Nathan Vos in GPU Pro 5). The benefit of using particles is that they are very easy to author. I can easily make particles come out of vents and manholes. I can use flipbooks and easily make a misty swamp with the system.  

I wanted the environment to be very atmospheric and unnerving. For this I made a custom fog solution that blends seamlessly into the HDRI and has some atmospheric scattering. 

Doing this in shader has the added benefit of making the sky and fog react dynamically to the directional light:

{% include imagenourl.html image="projects/volumetric/DynamicSky.gif" %}