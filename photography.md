---
layout: splash
title: Photography
permalink: /photography/
---

<div class="portfolio">
  <div class="photo">
    <img src="https://jarla-t.github.io/assets/images/Ocean_Svalbard.JPG" alt="Photo 1">
    <div class="overlay">© Jarla Thiesbrummel</div>
  </div>
  <div class="photo">
    <img src="https://jarla-t.github.io/assets/images/Mountains_Svalbard2.JPG" alt="Photo 2">
    <div class="overlay">© Jarla Thiesbrummel</div>
  </div>
  <div class="photo">
    <img src="https://jarla-t.github.io/assets/images/Svalbard_1.jpg" alt="Photo 3">
    <div class="overlay">© Jarla Thiesbrummel</div>
  </div>
  <div class="photo">
    <img src="/assets/images/gallery/photo4.jpg" alt="Photo 4">
    <div class="overlay">© Jarla Thiesbrummel</div>
  </div>
</div>

<style>
.portfolio {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 40px; /* space between photos */
  padding: 20px;
}

.photo {
  position: relative;
  width: 100%;
  max-width: 1000px; /* controls maximum size of each image */
}

.photo img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
}

.overlay {
  position: absolute;
  bottom: 12px;
  right: 12px;
  background: rgba(0,0,0,0.6);
  color: #fff;
  font-size: 14px;
  padding: 6px 10px;
  border-radius: 4px;
  pointer-events: none;
}

.photo::after {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: transparent; /* invisible shield */
}
  
</style>

<script>
// Optional: disable right-click
document.addEventListener('contextmenu', event => event.preventDefault());
</script>

