---
layout: splash
title: " "
header:
  overlay_image: "https://jarla-t.github.io/assets/images/Mountains_Svalbard.JPG"
  overlay_filter: 0.2
excerpt: "Scientist • Adventurer • Climate Enthusiast"

---
<style>
/* Transparent overlay to block clicks on splash header */
.splash-header {
  position: relative;
}

/* Full transparent overlay that catches clicks/taps */
.splash-header::before {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0); /* fully transparent */
  z-index: 1000;             /* above everything */
  pointer-events: auto;       /* catch clicks and taps */
  cursor: not-allowed;
}

/* Lock icon in top-right corner */
.splash-header::after {
  content: "🔒";
  position: absolute;
  top: 10px;
  right: 10px;
  font-size: 1.5rem;
  color: rgba(255,255,255,0.7);
  z-index: 1001; /* above overlay */
  pointer-events: none; /* allow overlay to catch clicks */
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
  const splash = document.querySelector(".splash-header");
  if (splash) {
    // Block right-click
    splash.addEventListener("contextmenu", e => e.preventDefault());
    // Block drag
    splash.addEventListener("dragstart", e => e.preventDefault());
    // Block tap-and-hold on mobile
    splash.addEventListener("touchstart", e => e.preventDefault());
  }
});
</script>



<div style="display: flex; align-items: center; gap: 1rem; margin-top: 2rem;">

  <!-- Image with overlay -->
<div style="
  position: relative;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  overflow: hidden;
  flex-shrink: 0; /* prevents shrinking on mobile */
  border: 2px solid white;
">
  <img
    src="https://jarla-t.github.io/assets/images/Oxfordpicture.jpg"
    alt="Jarla Thiesbrummel"
    draggable="false"
    oncontextmenu="return false;"
    style="
      width: 100%;
      height: auto;   /* keep aspect ratio */
      max-height: 100%;
      object-fit: cover;
      display: block;
    "
  >
  <!-- Transparent overlay -->
  <div style="
    position: absolute;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0);
    z-index: 2;
    pointer-events: auto;
    cursor: not-allowed;
    border-radius: 50%; /* ensures overlay stays circular */
  " oncontextmenu="return false;"></div>
</div>


  <p style="margin: 0;">
    Welcome! I’m a scientist fascinated by how technology and nature intersect.
    On this site, you’ll find my research, publications, and
    <a href="https://jarla-t.github.io/cv/" style="text-decoration: underline; color: inherit;">CV</a>
    — but also my personal projects and photography.
  </p>
</div>





<!--<br style="line-height: 3em;">
Welcome! I’m a scientist fascinated by how technology and nature intersect.  
On this site, you’ll find my research, publications, and <a href="https://jarla-t.github.io/cv/" style="text-decoration: underline; color: inherit;">CV</a> — but also my personal projects and photography.-->

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 2rem;">

  <a href="/research/" style="flex: 1 1 300px; position: relative; color: white; text-decoration: none; border-radius: 8px; overflow: hidden; aspect-ratio: 1 / 1; min-width: 280px;">
    <img src="https://jarla-t.github.io/assets/images/Cover2.JPG" 
         alt="Research" 
         style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; filter: brightness(0.9);">
    <div style="position: absolute; bottom: 0; left: 0; width: 100%; padding: 15px; background: rgba(0,0,0,0.3);">
      <h3 style="margin: 0 0 0.5rem;">Research</h3>
      <p style="margin: 0;">Perovskites, solar cells, and climate-related materials science.</p>
    </div>
  </a>

  <a href="/hobbies/" style="flex: 1 1 300px; position: relative; color: white; text-decoration: none; border-radius: 8px; overflow: hidden; aspect-ratio: 1 / 1; min-width: 280px;">
    <img src="https://jarla-t.github.io/assets/images/Mountains_Svalbard2.JPG" 
         alt="Hobbies" 
         style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; filter: brightness(0.9);">
    <div style="position: absolute; bottom: 0; left: 0; width: 100%; padding: 15px; background: rgba(0,0,0,0.3);">
      <h3 style="margin: 0 0 0.5rem;">Hobbies</h3>
      <p style="margin: 0;">Arctic exploration, learning languages, outdoor adventures.</p>
    </div>
  </a>

  <a href="/photography/" style="flex: 1 1 300px; position: relative; color: white; text-decoration: none; border-radius: 8px; overflow: hidden; aspect-ratio: 1 / 1; min-width: 280px;">
    <img src="https://jarla-t.github.io/assets/images/Ocean_Svalbard.JPG" 
         alt="Photography" 
         style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; filter: brightness(0.9);">
    <div style="position: absolute; bottom: 0; left: 0; width: 100%; padding: 15px; background: rgba(0,0,0,0.3); text-align: center;">
      <h3 style="margin: 0 0 0.5rem;">Photography</h3>
      <p style="margin: 0;">Capturing the beauty of nature and life in the Arctic.</p>
    </div>
  </a>

</div>



