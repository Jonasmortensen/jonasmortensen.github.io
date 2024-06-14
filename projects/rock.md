---
layout: post
title: 'Toon Rock'
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
    src="https://www.youtube.com/embed/Z_lwsTMIBEA?playlist=Z_lwsTMIBEA&autoplay=1&mute=1&enablejsapi=1&controls=0&loop=1"
    frameborder="0"
></iframe>
</div>

I had this idea for an art style where the environment is rendered in 3D but characters and dynamic objects feel 2D. That resulted in this small proof of concept. 

The rock is a physics simulated 3D mesh but is rendered by an orthographic camera off screen and then put on screen as a billboard. It makes it seems like the rock was 2D animated specifically for this movement but actually it's all rendered real time based on player input. 