---
title: photos
layout: default
permalink: /photos/
nav: false
nav_order: 10
---

# photos

<!-- Welcome to my photo gallery! Here you’ll find a collection of images. -->

<div class="gallery">
  {% assign url1 = "/assets/img/sc_rmz.jpg" %}
  {% assign alt1 = "" %}
  {% assign caption1 = "Atlanta, Fall 2024<br>with my Ph.D. colleague, Sanil Rao (left), and our former postdoc, Het Mankad (middle)" %}
  
  {% assign url2 = "/assets/img/cmu_ffz.jpg" %}
  {% assign alt2 = "" %}
  {% assign caption2 = "Pittsburgh, Winter 2024<br>with my undergraduate mentee, Sophia Fu (left), and my advisor, Franz Franchetti (middle)" %}

  {% assign url3 = "/assets/img/usc_seminar.jpg" %}
  {% assign alt3 = "" %}
  {% assign caption3 = "Los Angeles, Summer 2025<br>with my undergraduate advisor, Viktor K. Prasanna (center), and a full room of USC students" %}

  <div class="gallery-item">
    <img src="{{ url1 }}" alt="{{ alt1 }}" loading="lazy">
    <p>{{ caption1 }}</p>
  </div>
  
  <div class="gallery-item">
    <img src="{{ url2 }}" alt="{{ alt2 }}" loading="lazy">
    <p>{{ caption2 }}</p>
  </div>

  <div class="gallery-item">
    <img src="{{ url3 }}" alt="{{ alt3 }}" loading="lazy">
    <p>{{ caption3 }}</p>
  </div>

</div>

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr);  /* This ensures two photos per row */
    gap: 16px;
    margin-top: 16px;
  }

  .gallery-item {
    text-align: center;
  }

  .gallery-item img {
    max-width: 100%;
    width: 80%; /* Make the images smaller */
    height: auto;
    border-radius: 8px;
  }
</style>





