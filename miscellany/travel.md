---
layout: page
title: Travel
permalink: /miscellany/travel/

---

<style>
.gallery {
    --n: 3; /* number of rows*/
    --m: 4; /* number of columns */
    --h: calc((100vh - (var(--n) - 1)*var(--g))/var(--n));
    --w: calc((100vw - (var(--m) - 1)*var(--g))/var(--m)); 
    --g: 10px;  /* control the gap */
    --f: 1.5;   /* control the scale factor */
    
    display: grid;
    gap: var(--g);
    width: 100vw;
    height: 100vh;
    grid-template-columns: repeat(var(--m),auto);
  }
  
  .gallery > img {
    width: 0;
    height: 0;
    min-height: 100%;
    min-width: 100%;
    object-fit: cover;
    cursor: pointer;
    filter: grayscale(80%);
    transition: .35s linear;
  }
  
  .gallery img:hover{
    filter: grayscale(0);
    width:  calc(var(--w)*var(--f));
    height: calc(var(--h)*var(--f));
  }
  
  
  body {
    margin: 0;
    background: #60c4ff;
  }
</style>

<div class="gallery">
  <img src="https://picsum.photos/id/1028/400/400" alt="a forest after an apocalypse">
  <img src="https://picsum.photos/id/15/400/400" alt="a waterfall and many rocks">
  <img src="https://picsum.photos/id/1040/400/400" alt="a house on a mountain">
  <img src="https://picsum.photos/id/106/400/400" alt="sime pink flowers">
  <img src="https://picsum.photos/id/136/400/400" alt="big rocks with some trees">
  <img src="https://picsum.photos/id/1039/400/400" alt="a waterfall, a lot of tree and a great view from the sky">
  <img src="https://picsum.photos/id/110/400/400" alt="a cool landscape">
  <img src="https://picsum.photos/id/1047/400/400" alt="inside a town between two big buildings">
  <img src="https://picsum.photos/id/1057/400/400" alt="a great view of the sea above the mountain">
  <img src="https://picsum.photos/id/1016/400/400" alt="a great view of a canyon">
  <img src="https://picsum.photos/id/1015/400/400" alt="a great view of a river between mountains">
  <img src="https://picsum.photos/id/1020/400/400" alt="a wild bear appeared">
</div>