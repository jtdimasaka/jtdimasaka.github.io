---
layout: page
permalink: /dimasakawoodcarvings/
title: Dimasaka Wood Carvings
---

<!-- Instagram-style responsive photo collage -->

<style>
  .collage {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    justify-content: center;
    padding: 10px;
  }

  .collage img {
    width: 100%;
    height: auto;
    object-fit: cover;
    border-radius: 8px;
  }

  .collage-item {
    flex: 1 1 calc(33.333% - 16px);
    max-width: calc(33.333% - 16px);
  }

  @media (max-width: 768px) {
    .collage-item {
      flex: 1 1 calc(50% - 16px);
      max-width: calc(50% - 16px);
    }
  }

  @media (max-width: 480px) {
    .collage-item {
      flex: 1 1 100%;
      max-width: 100%;
    }
  }
</style>

<div class="collage">
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 1">
  </div>
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 2">
  </div>
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 3">
  </div>
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 4">
  </div>
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 5">
  </div>
  <div class="collage-item">
    <img src="/images/profile.jpg" alt="Image 6">
  </div>
</div>
