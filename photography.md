---
layout: splash
title: Photography
permalink: /photography/
---

<div class="gallery">
  <div class="photo">
    <img src="/assets/images/gallery/photo1.jpg" alt="Photo 1">
    <div class="overlay">© Your Name</div>
  </div>
  <div class="photo">
    <img src="/assets/images/gallery/photo2.jpg" alt="Photo 2">
    <div class="overlay">© Your Name</div>
  </div>
  <div class="photo">
    <img src="/assets/images/gallery/photo3.jpg" alt="Photo 3">
    <div class="overlay">© Your Name</div>
  </div>
  <div class="photo">
    <img src="/assets/images/gallery/photo4.jpg" alt="Photo 4">
    <div class="overlay">© Your Name</div>
  </div>
</div>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.photo {
  position: relative;
}

.photo img {
  width: 300px;
  height: auto;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

.overlay {
  position: absolute;
  bottom: 8px;
  right: 8px;
  background: rgba(0,0,0,0.6);
  color: #fff;
  font-size: 14px;
  padding: 4px 8px;
  border-radius: 4px;
  pointer-events: none; /* stops overlay from blocking */
}
</style>

<script>
// Optional: disable right-click
document.addEventListener('contextmenu', event => event.preventDefault());
</script>
