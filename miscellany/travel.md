---
layout: page
title: Travel
permalink: /miscellany/travel/

---

<style>
*
  box-sizing border-box

body
  min-height 100vh
  display flex
  align-items center
  justify-content center

.image-container
  display grid
  grid-template-columns repeat(3, 1fr)
  grid-template-rows repeat(3, 1fr)
  width 600px
  grid-gap 0.5rem

  .image
    position relative
    padding-bottom 100%

    img
      height 100%
      width 100%
      object-fit cover
      left 0
      position absolute
      top 0

    img:nth-of-type(1)
      filter grayscale(1) brightness(40%)

    img:nth-of-type(2)
      clip-path var(--clip-start)
      transition clip-path 0.5s

    &:hover img:nth-of-type(2)
      clip-path var(--clip-end)
</style>


<div class="image-container">
  <div class="image" style="--clip-start: ellipse(0 0 at 0 0); --clip-end: ellipse(150% 150% at 0 0);"><img src="https://i.picsum.photos/id/21/200/200.jpg?hmac=a2iQ6UhOjpU6jn7QSsCpk1CiiKTxmW1R4UivDsv-n8o"/><img src="https://i.picsum.photos/id/21/200/200.jpg?hmac=a2iQ6UhOjpU6jn7QSsCpk1CiiKTxmW1R4UivDsv-n8o"/></div>
  <div class="image" style="--clip-start: inset(100% 0 0 0); --clip-end: inset(0 0 0 0);"><img src="https://i.picsum.photos/id/139/200/200.jpg?hmac=FNSPvHsHcRzKQtNxKKauJgIXpoaAufCwYvr-1w5T3R4"/><img src="https://i.picsum.photos/id/139/200/200.jpg?hmac=FNSPvHsHcRzKQtNxKKauJgIXpoaAufCwYvr-1w5T3R4"/></div>
  <div class="image" style="--clip-start: ellipse(0 0 at 100% 0); --clip-end: ellipse(150% 150% at 100% 0);"><img src="https://i.picsum.photos/id/642/200/200.jpg?hmac=MJkhEaTWaybCn0y7rKfh_irNHvVuqRHmxcpziWABTKw"/><img src="https://i.picsum.photos/id/642/200/200.jpg?hmac=MJkhEaTWaybCn0y7rKfh_irNHvVuqRHmxcpziWABTKw"/></div>
  <div class="image" style="--clip-start: polygon(50% 50%,  50% 50%,  50% 50%, 50% 50%); --clip-end: polygon(-50% 50%, 50% -50%, 150% 50%, 50% 150%);"><img src="https://i.picsum.photos/id/253/200/200.jpg?hmac=_dceojr9yz5ZIKoye8I9HOqPCBHfn-jT9aRYdoLx1kQ"/><img src="https://i.picsum.photos/id/253/200/200.jpg?hmac=_dceojr9yz5ZIKoye8I9HOqPCBHfn-jT9aRYdoLx1kQ"/></div>
  <div class="image" style="--clip-start: circle(0); --clip-end: circle(125%);"><img src="https://i.picsum.photos/id/604/200/200.jpg?hmac=qgFjxODI1hMBMfHo68VvLeji-zvG9y-iPYhyW0EkvOs"/><img src="https://i.picsum.photos/id/604/200/200.jpg?hmac=qgFjxODI1hMBMfHo68VvLeji-zvG9y-iPYhyW0EkvOs"/></div>
  <div class="image" style="--clip-start: inset(100% 100% 100% 100%); --clip-end: inset(0 0 0 0);"><img src="https://i.picsum.photos/id/119/200/200.jpg?hmac=JGrHG7yCKfebsm5jJSWw7F7x2oxeYnm5YE_74PhnRME"/><img src="https://i.picsum.photos/id/119/200/200.jpg?hmac=JGrHG7yCKfebsm5jJSWw7F7x2oxeYnm5YE_74PhnRME"/></div>
  <div class="image" style="--clip-start: ellipse(0 0 at 0 100%); --clip-end: ellipse(150% 150% at 0 100%);"><img src="https://i.picsum.photos/id/520/200/200.jpg?hmac=gq6GVKg64GMqsvk_d6gzXZ7L1htska1jEdgBnAwm4xU"/><img src="https://i.picsum.photos/id/520/200/200.jpg?hmac=gq6GVKg64GMqsvk_d6gzXZ7L1htska1jEdgBnAwm4xU"/></div>
  <div class="image" style="--clip-start: inset(0 0 100% 0); --clip-end: inset(0 0 0 0);"><img src="https://i.picsum.photos/id/553/200/200.jpg?hmac=HSLKzqqoxnajv4KjLxYSjZokWcuCCiZLGdRPUoryhXk"/><img src="https://i.picsum.photos/id/553/200/200.jpg?hmac=HSLKzqqoxnajv4KjLxYSjZokWcuCCiZLGdRPUoryhXk"/></div>
  <div class="image" style="--clip-start: ellipse(0 0 at 100% 100%); --clip-end: ellipse(150% 150% at 100% 100%);"><img src="https://i.picsum.photos/id/988/200/200.jpg?hmac=-lwK-i6PssD9WlUeVPDIhOxDVxlzJKeM4MgEx_fIqJg"/><img src="https://i.picsum.photos/id/988/200/200.jpg?hmac=-lwK-i6PssD9WlUeVPDIhOxDVxlzJKeM4MgEx_fIqJg"/></div>
</div>