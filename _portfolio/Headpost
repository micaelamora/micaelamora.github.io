---
title: "Head Post"
category: personal
excerpt: "Head Post used to study neural activities in mice and monkeys"
header:
  image: /assets/img/headset.png
  teaser: /assets/img/headset.png
gallery:
  - image_path: /assets/img/headset.png
  - image_path: /assets/img/headset.png
  - image_path: /assets/img/headset.png
---
<!-- Wrapper for page-specific styling -->
<div class="headpost-page">

  <!-- Header Image -->
  <img src="{{ page.header.image }}" alt="Head Post Header" class="headpost-header" />

  <!-- Page Title -->
  <h1>Head Post</h1>

  <!-- Section Title -->
  <h2>CAD Model</h2>

  <!-- CAD Model iframe -->
  <iframe
    src="https://a360.co/45LegEo"
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
      <a href="{{ item.image_path }}" class="glightbox" data-gallery="headpost">
        <img src="{{ item.image_path }}" alt="Gallery image" class="gallery-thumb" />
      </a>
    {% endfor %}
  </div>

</div>

<!-- GLightbox CSS & JS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css" />
<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // Initialize GLightbox once the page is loaded
  const lightbox = GLightbox({
    selector: '.glightbox',
    closeOnOutsideClick: true
  });
});
</script>

<!-- Page-specific Styling -->
<style>
/* Only applies to Head Post page */
.headpost-page .headpost-header {
  width: 300px; /* Smaller header image */
  height: auto;
  display: block;
  margin: 20px auto; /* Center it */
}

/* Gallery Grid */
.headpost-page .gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  margin-top: 20px;
}

.headpost-page .gallery-thumb {
  width: 100%;
  height: auto;
  object-fit: cover;
  border-radius: 8px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

.headpost-page .gallery-thumb:hover {
  transform: scale(1.05);
}
</style>
