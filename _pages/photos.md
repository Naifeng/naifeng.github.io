---
title: photos
layout: default
permalink: /photos/
nav: true
nav_order: 10
---

# photos

<!-- Welcome to my photo gallery! Here you’ll find a collection of images. -->

<div class="gallery">
  {% assign url1 = "/assets/img/sc_rmz.jpg" %}
  {% assign alt1 = "" %}
  {% assign caption1 = "Atlanta, Fall 2024<br>with Sanil Rao (left), my Ph.D. colleague, and Het Mankad (middle), our former postdoc" %}
  
  {% assign url2 = "/assets/img/cmu_ffz.jpg" %}
  {% assign alt2 = "" %}
  {% assign caption2 = "Pittsburgh, Winter 2024<br>with Sophia Fu (left), my undergraduate mentee, and Franz Franchetti (middle), my advisor" %}

  <!-- {% assign url3 = "/assets/img/cmu_ffz.jpg" %}
  {% assign alt3 = "A city skyline" %}
  {% assign caption3 = "City skyline at night" %} -->

  <div class="gallery-item">
    <img src="{{ url1 }}" alt="{{ alt1 }}" loading="lazy">
    <p>{{ caption1 }}</p>
  </div>
  
  <div class="gallery-item">
    <img src="{{ url2 }}" alt="{{ alt2 }}" loading="lazy">
    <p>{{ caption2 }}</p>
  </div>

  <!-- <div class="gallery-item">
    <img src="{{ url3 }}" alt="{{ alt3 }}" loading="lazy">
    <p>{{ caption3 }}</p>
  </div> -->
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





