---
layout: page
title: Projects
permalink: /projects/
---

<!-- <ul>
	<li><a href="ArcticCCAM">Arctic Climate Change Adaptation and Mitigation using Causal Graph Inference</a></li>
	<li><a href="SeaIceDL">Antarctica Sea Ice Classification using Convolutional Neural Network</a></li>
	<li><a href="EarthquakeGMMA">Regional Earthquake Resilience of the Greater Metro Manila Area, Philippines</a></li>
	<li><a href="VBCI">Seismic Multi-hazard and Impact Estimation via Causal Inference from Satellite Imagery</a></li>
</ul> -->

<div class="supports"></div>

<ul class="list img-list">
  <li>
    <a href="ArcticCCAM" class="inner">
      <div class="li-img">
        <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/12005/balloon-sq1.jpg" alt="" />
      </div>
      <div class="li-text">
        <h3 class="li-head">Arctic Climate Change Adaptation and Mitigation using Causal Graph Inference</h3>
        <div class="li-sub">
          <p>...</p>
        </div>
      </div>
    </a>
  </li>
  <li>
    <a href="SeaIceDL" class="inner">
      <div class="li-img">
        <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/12005/balloon-sq2.jpg" alt="" />
      </div>
      <div class="li-text">
       <h3 class="li-head">Antarctica Sea Ice Classification using Convolutional Neural Network</h3>
        <div class="li-sub">
          <p>...</p>
        </div>
      </div>
    </a>
  </li>
  <li>
    <a href="EarthquakeGMMA" class="inner">
      <div class="li-img">
        <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/12005/balloon-sq3.jpg" alt="Hot air balloons" />
      </div>
      <div class="li-text">
        <h3 class="li-head">Regional Earthquake Resilience of the Greater Metro Manila Area, Philippines</h3>
        <div class="li-sub">
          <p>...</p>
          <p>...</p>
          <p>...</p>
        </div>
      </div>
    </a>
  </li>
  <li>
    <a href="VBCI" class="inner">
      <div class="li-img">
        <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/12005/balloon-sq4.jpg" alt="Hot air balloons" />
      </div>
      <div class="li-text">
        <h3 class="li-head">Seismic Multi-hazard and Impact Estimation via Causal Inference from Satellite Imagery</h3>
        <div class="li-sub">
          <p>...</p>
        </div>
      </div>
    </a>
  </li>
 
</ul>

<style>
	.list {
	max-width: 1400px;
	margin: 20px auto;
	}

	.img-list a {
	text-decoration: none;
	}

	.li-sub p {
	margin: 0;
	}

	.list li {
	border-bottom: 1px solid #ccc;
	display: table;
	border-collapse: collapse;
	width: 100%;
	}
	.inner {
	display: table-row;
	overflow: hidden;
	}
	.li-img {
	display: table-cell;
	vertical-align: middle;
	width: 30%;
	padding-right: 1em;
	}
	.li-img img {
	display: block;
	width: 100%;
	height: auto;
	
	}
	.li-text {
	display: table-cell;
	vertical-align: middle;
	width: 70%;
	}
	.li-head {
	margin: 10px 0 0 0;
	}
	.li-sub {
	margin: 0;
	}

	@media all and (min-width: 45em) {
	.list li {
		float: left;
		width: 50%;
	}
	}

	@media all and (min-width: 75em) {
	.list li {
		width: 33.33333%;
	}
	}

	/* for flexbox */
	@supports(display: flex) {
	.list {
		display: flex;
		flex-wrap: wrap;
	}
	
	.li-img,
	.li-text,
	.list li {
		display: block;
		float: none;
	}

	.li-img {
		align-self: center; /* to match the middle alignment of the original */
	}
	
	.inner {
		display: flex;
	}
	}

	/* for grid */
	@supports(display: grid) {
	.list {
		display: grid;
		grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
	}
	
	.list li {
		width: auto; /* this overrides the media queries */
	}
	}
</style>