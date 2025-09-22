---
layout: page
title: Optimal Projectile Interception
description: Using the Bellman equation to solve a multi-period resource allocation problem
img: assets/img/opt_proj.JPG
importance: 2
category: work
giscus_comments: false
---

I worked on this project just for fun over the summer of 2025. The project formulates a resource allocation problem where one is faced with allocating an optimal number of "interceptors" across an incoming number of "projectiles" which impose a cost if they aren't intercepted. The single-period version of the problem is solved using integer programming, while the multi-period version is solved using dynamic programming. For a special case of the multi-period problem one can use value iteration. I have yet to make the code repository available, but the Latex document is available below.

<style>
.pdf-container {
  position: relative;
  width: 95%;
  height: 0;
  padding-bottom: 120%;
}

.pdf-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}
</style>

<div class="pdf-container">
  <iframe src="/assets/pdf/proj_intercept.pdf" frameborder="0"></iframe>
</div>
