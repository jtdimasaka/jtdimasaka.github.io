---
layout: page
title: Projects
permalink: /projects/
---

<ul>
	<li><a href="ArcticCCAM">Arctic Climate Change Adaptation and Mitigation using Causal Graph Inference</a></li>
	<li><a href="SeaIceDL">Antarctica Sea Ice Classification using Convolutional Neural Network</a></li>
	<li><a href="EarthquakeGMMA">Regional Earthquake Resilience of the Greater Metro Manila Area, Philippines</a></li>
	<li><a href="VBCI">Seismic Multi-hazard and Impact Estimation via Causal Inference from Satellite Imagery</a></li>
</ul>

<main>

  <section class="news-feed">
    <img src="http://via.placeholder.com/293x293">
    <img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293"><img src="http://via.placeholder.com/293x293">
  </section>

</main>

<style>
	html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}

body {
  background: #ddd;
}

.header {
  background: white;
  color: #333;
  position: fixed;
  left: 0;
  right: 0;
  height: 40px;
  top:0;
}

.header-content {
  max-width: 930px;
  margin: 0 auto;
  display: flex;
  height: 100%;
  justify-content: space-between;
  align-items: center;
  input {
    display: none;
  }
}

@media (min-width: 700px) {
  .header-content input {
    display:block;
  }
}


.main-nav {
  > ul {
    margin: 0;
    padding: 0;
    list-style: none;
    > li {
      display: inline-block;
    }
  }
}

main {
  max-width: 930px;
  margin: 4rem auto;
  border: 3px dashed red;
}

.avatar {
  border-radius: 50%;
  width: 70px;
  justify-self: center;
}

.user-info {
  border: 3px dashed blue;
  display: grid;
  padding: 10px;
  grid-template-columns: 1fr 4fr;
  grid-template-rows: repeat(3, auto);
  h1 {
    margin: 0;
  }
  p {
    grid-column: 1 / -1;
  }
  .user-stats {
    grid-column: 1 / -1;
    grid-row: 3;
    display: flex;
    justify-content: space-around;
  }
}

@media (min-width: 700px) {
  .user-info {
    grid-template-columns: 1fr 2fr;
    p {
      grid-column: auto;
    }
    .user-stats {
      grid-column: auto;
      grid-row: auto;
      display: block;
    }
  }
  .avatar {
    width: 152px;
    grid-row: 1 / -1;
  }
}


.news-feed {
  border: 3px dashed blue;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5px;
  img {
    width: 100%;
  }
}

@media (min-width: 700px) {
  .news-feed {
    grid-gap: 28px;
  }
}

.feed-nav {
  display: flex;
  justify-content: center;
  a {
    display:block;
    padding: 10px;
  }
}

</style>