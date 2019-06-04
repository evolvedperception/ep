---
layout: contentpage
title: Artwork and Photography
---

<!--
<section class="gallery" aria-labelledby="photoGalleryHeading">
<h2 id="photoGalleryHeading">Photography</h2>
{% for image in site.static_files %}
{% if image.path contains 'images/ep/artwork/photography' %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }} Photograph" />
{% endif %}
{% endfor %}
</section>
-->

<!--
<section class="gallery" aria-labelledby="artGalleryHeading">
<h2 id="photoGalleryHeading">Watercolor Paintings</h2>
{% for image in site.static_files %}
{% if image.path contains 'images/ep/artwork/watercolor' %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }} Watercolor Painting" />
{% endif %}
{% endfor %}
</section>

-->

<style>


</style>


<!-- image sizes
Tall: 400W x 600H
square: 400 x 400
Wide: 600px wide  x 400H
-->



<section class="gallery">
<div class="row" style="clear: both;"> 
  <div class="column">
    <img src="/images/ep/artwork/photography/coneflowerA.jpg" alt="coneflower photograph" style="width:100%">
    <img src="/images/ep/artwork/watercolor/watercolor1.jpg" alt="coneflower watercolor painting" style="width:100%">
  </div>
  <div class="column">
    <img src="/images/ep/artwork/photography/flowerA.jpg" alt="hellenium photograph" style="width:100%">
    <img src="/images/ep/artwork/watercolor/watercolor2.jpg" alt="columbine watercolor painting" style="width:100%">
  </div>
      <div class="column">
    <img src="/images/ep/artwork/photography/hostaA.jpg" alt="cup hosta photograph" style="width:100%">
    <img src="/images/ep/artwork/watercolor/watercolor3.jpg" alt="sweet pea watercolor painting" style="width:100%">
  </div>
  <div class="column">
    <img src="/images/ep/artwork/photography/zinniaB.jpg" alt="zinnia photograph" style="width:100%">
  </div>
</div>
</section>