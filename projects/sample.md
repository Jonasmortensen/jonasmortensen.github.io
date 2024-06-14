---
layout: post
title: 'URP Sample Scenes'
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
    src="https://www.youtube.com/embed/95caVrs6T4M?playlist=95caVrs6T4M&autoplay=1&mute=1&enablejsapi=1&controls=1&loop=1"
    frameborder="0"
    allowfullscreen
></iframe>
</div>

While at Unity I was responsible for delivering this collection of scenes. I did technical art work on each of the scenes as well as art direction and general concept development. 

For moving between the scenes I created the seamless dissolve effect that can be seen at 0:20 in the video. The effect doesn't assume camera position and works well in first person.

One of the main challenges when making the scenes was performance optimizing. The scenes needed to run on a selection of target hardware with different limitations and challenges including iPhone 6s, Nintendo Switch and Meta Quest 2.

