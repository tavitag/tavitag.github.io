---
layout: page
title: Gallery
---

Short electrical image movies of neurons in retinal tissue, recorded with a multielectrode array. Each frame shows the voltage footprint of spiking activity across the array.

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0;
}
.gallery figure { margin: 0; }
.gallery video,
.gallery img {
  display: block;
  width: 100%;
  height: auto;
  background: #000;
}
.gallery figcaption {
  margin-top: .4rem;
  font-size: .85rem;
  color: #717171;
}
</style>

<div class="gallery">

  <figure>
    <video controls loop muted playsinline preload="metadata">
      <source src="{{ '/public/movies/EI-movie-unit_221_ScalePct_99.0_gamma_0.8.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption><strong>Unit 221.</strong> Scale 99th percentile, gamma 0.8.</figcaption>
  </figure>

  <figure>
    <video controls loop muted playsinline preload="metadata">
      <source src="{{ '/public/movies/EI-movie-unit_207_ScalePct_99.0_gamma_0.8.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption><strong>Unit 207.</strong> Scale 99th percentile, gamma 0.8.</figcaption>
  </figure>

  <figure>
    <video controls loop muted playsinline preload="metadata">
      <source src="{{ '/public/movies/EI-movie-unit_16_ScalePct_99.0_gamma_0.8.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption><strong>Unit 16.</strong> Scale 99th percentile, gamma 0.8.</figcaption>
  </figure>

</div>
