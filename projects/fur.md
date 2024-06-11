---
layout: post
title: 'Fur Rendering'
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
    src="https://www.youtube.com/embed/gv93eIrY0Ys?playlist=gv93eIrY0Ys&autoplay=1&mute=1&enablejsapi=1&controls=0&loop=1"
    frameborder="0"
></iframe>
</div>

I watched a video online about doing grass and fur using mesh shells. It inspired me to try out the method myself. As a way to practice my compute shader skills I added simple physics to the fur. The simulation runs per vertex in the shell mesh (not per hair strand).



<div class="video-holder">
  <iframe
    id="existing-iframe-example"
    width="640" height="360"
    src="https://www.youtube.com/embed/CQ9u4auBVXo?playlist=CQ9u4auBVXo&mute=1&enablejsapi=1&controls=0&loop=1"
    frameborder="0"
></iframe>
</div>