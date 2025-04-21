---
layout: page
permalink: /dimasakawoodcarvings/
title: Dimasaka Wood Carvings
---



<style>
  .collage {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    justify-content: center;
    padding: 10px;
  }

  .collage figure {
    margin: 0;
    flex: 1 1 calc(33.333% - 16px);
    max-width: calc(33.333% - 16px);
  }

  .collage img {
    width: 100%;
    height: auto;
    object-fit: cover;
    border-radius: 8px;
    display: block;
  }

  .collage figcaption {
    font-size: 0.75rem;
    text-align: center;
    margin-top: 4px;
    color: #555;
  }

  @media (max-width: 768px) {
    .collage figure {
      flex: 1 1 calc(50% - 16px);
      max-width: calc(50% - 16px);
    }
  }

  @media (max-width: 480px) {
    .collage figure {
      flex: 1 1 100%;
      max-width: 100%;
    }
  }
</style>

<div class="collage">
  <figure>
    <img src="/images/profile.jpg" alt="Image 1">
    <figcaption>Caption 1</figcaption>
  </figure>
  <figure>
    <img src="/images/profile.jpg" alt="Image 2">
    <figcaption>Caption 2</figcaption>
  </figure>
  <figure>
    <img src="/images/profile.jpg" alt="Image 3">
    <figcaption>Caption 3</figcaption>
  </figure>
  <figure>
    <img src="/images/profile.jpg" alt="Image 4">
    <figcaption>Caption 4</figcaption>
  </figure>
  <figure>
    <img src="/images/profile.jpg" alt="Image 5">
    <figcaption>Caption 5</figcaption>
  </figure>
  <figure>
    <img src="/images/profile.jpg" alt="Image 6">
    <figcaption>Caption 6</figcaption>
  </figure>
</div>
