---
layout: page
title: Optimal Projectile Interception
description: Using the Bellman equation to solve a multi-period resource allocation problem
img: assets/img/opt_proj.png
importance: 2
category: work
giscus_comments: false
---

I worked on this project just for fun over the summer of 2025. The project formulates a resource allocation problem where one is faced with allocating an optimal number of "interceptors" across an incoming number of "projectiles" which impose a cost if they aren't intercepted. The single-period version of the problem is solved using integer programming, while the multi-period version is solved using dynamic programming. For a special case of the multi-period problem one can use value iteration. I have yet to make the code repository available, but the Latex document is available below.

<embed src="/assets/pdf/proj_intercept.pdf" 
       type="application/pdf" 
       width="800px" 
       height="1200px"
       style="border: 1px solid #ccc;" />
