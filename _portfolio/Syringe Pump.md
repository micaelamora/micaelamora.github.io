---
title: "Syringe Pump"
category: fabrication
excerpt: "New Born Feeder syringe pump with interchangeables 5ml, 10ml, 15ml"
header:
  image: /assets/img/Assembly_of_Linear_Actuator_2026-Jan-10_11-08-09PM-000_CustomizedView8386927097_png.png
  teaser: /assets/img/syringe pump.png
gallery:
  - thumb: /assets/img/syringe pump.png
    full: /assets/img/syringe pump.png
  - thumb: /assets/img/syringe pump.png
    full: /assets/img/syringe pump.png
  - thumb: /assets/img/syringe pump.png
    full: /assets/img/syringe pump.png
---
<!-- Wrapper for page-specific styling -->
<div class="syringe-page">

  <!-- Features Section -->
  <h2>Features</h2>

  <ul>
    <li><strong>There are 5 buttons and a knob accessible on the syringe pump.</strong> 
      Starting from the left, the first button is the fast forward or mechanical forward button. When pushed and held down, the syringe moves at a rate of 25.65 mL per minute for the 20 mL syringe, and 15.85 mL for the 10 mL syringe. Similarly, the second button, the reverse button, retracts the syringe at the same rates. The third button starts/pauses automatic motion at the default flow rate. The fourth button adjusts the rate for the 10 mL syringe. The fifth button switches flow control to the potentiometer knob.
    </li>
    <li><strong>Interchangeable between 10 mL and 20 mL syringes.</strong> 
    </li>
    <li><strong>Smooth and accessible design.</strong> The PLA enclosure protects electronics while making buttons easily accessible. Holes for power wires, latches, and microcontroller connections are tight-fitting to prevent intrusion.
    </li>
  </ul>

  <!-- CAD Model Section -->
  <h2>CAD Model</h2>
  <iframe
    src="https://a360.co/4qGvStc?mode=embed"
    width="800"
    height="600"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0">
  </iframe>

  <!-- Gallery Section -->
  <div class="gallery-grid">
    {% for item in page.gallery %}
      <a href="{{ item.full }}" class="glightbox" data-gallery="syringe">
        <img src="{{ item.thumb }}" alt="Gallery image" class="gallery-thumb" />
      </a>
    {% endfor %}
  </div>

</div>

<!-- GLightbox CSS & JS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css" />
<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const lightbox = GLightbox({
    selector: '.glightbox',
    closeOnOutsideClick: true
  });
});
</script>

<!-- Page-specific Styling -->
<style>
/* Syringe Pump page only */
.syringe-page .syringe-header {
  width: 300px;
  height: auto;
  display: block;
  margin: 20px auto 40px auto; /* Center and add spacing */
}

/* Gallery Grid */
.syringe-page .gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  margin-top: 20px;
}

.syringe-page .gallery-thumb {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 8px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

.syringe-page .gallery-thumb:hover {
  transform: scale(1.05);
}
</style>
