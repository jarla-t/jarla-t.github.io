---
layout: single
title: Hobbies
permalink: /hobbies/
---

I enjoy Arctic exploration and aim to spread awareness about climate change.

<div class="image-overlay">
  <img src="/assets/images/Mountains_Svalbard2.JPG" alt="Trollsteinen">
  <div class="overlay-text">© Jarla Thiesbrummel. Do Not Download</div>
</div>

<style>
.image-overlay {
  position: relative;
  display: inline-block;
}

.image-overlay img {
  display: block;
  pointer-events: none; /* Prevent dragging */
}

.image-overlay .overlay-text {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  color: white;
  background: rgba(0, 0, 0, 0.3); /* semi-transparent overlay */
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  text-align: center;
  pointer-events: none;
  user-select: none;
}

.image-overlay img,
.image-overlay .overlay-text {
  -webkit-user-drag: none;
  -webkit-touch-callout: none;
}
</style>
