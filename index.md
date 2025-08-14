---
layout: splash
title: " "
header:
  overlay_image: "https://jarla-t.github.io/assets/images/Mountains_Svalbard.JPG"
  overlay_filter: 0.2
excerpt: "Scientist • Adventurer • Climate Enthusiast"

---

<div style="display: flex; align-items: center; gap: 1rem; margin-top: 2rem;">

  <!-- Image with overlay protection -->
  <div style="position: relative; width: 100px; height: 100px;">
    <img
      src="https://jarla-t.github.io/assets/images/Oxfordpicture.jpg"
      alt="Jarla Thiesbrummel"
      draggable="false"
      style="
        width: 100%;
        height: 100%;
        object-fit: cover;
        display: block;
        border-radius: 50%;
        border: 2px solid white;
      "
    >
    <!-- Transparent overlay that intercepts right-click/long-press -->
    <span
      aria-hidden="true"
      oncontextmenu="return false;"
      style="
        position: absolute;
        inset: 0;                 /* top:0; right:0; bottom:0; left:0; */
        border-radius: 50%;
        background: rgba(0,0,0,0);/* for Safari, you can use 0.001 if needed */
        z-index: 1;
        pointer-events: auto;     /* capture clicks/right-clicks */
        cursor: not-allowed;      /* optional visual hint */
      "
    ></span>
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



