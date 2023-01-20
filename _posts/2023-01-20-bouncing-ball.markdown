---
layout: post
title:  "Bouncing ball animation test"
date:   2023-01-20
categories: animation
---

<div class="ball-container">
  <div class="ball"></div>
</div>

<style>
.ball-container {
  height: 300px;
  width: 100%;
  position: relative;
  overflow: hidden;
}

.ball {
  height: 50px;
  width: 50px;
  border-radius: 25px;
  background: red;
  position: absolute;
  top: 0;
  left: 0;
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0% {
    top: 0;
  }
  50% {
    top: 250px;
  }
  100% {
    top: 0;
  }
}
</style>
