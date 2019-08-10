---
title: "Tessellation Basics: Subdivision Surfaces"
categories:
  - Programming
  - Tag Trek
tags:
  - tessellation
---

One method of producing a 3D sphere is using a subdivision surfaces algorithm. Starting with only four equilateral triangles (making a pyramid), you then subdivide each triangle into four, smaller equilateral triangles. After the subdivision, the distance from the sphere's origin to each new vertex is normalized to the radius of the sphere. Repeat the process any number of times to continue dividing the surfaces. With enough triangles, the final mesh will appear as a smooth, curved surface.

Resource (image left): 3D Engine Design for Virtual Globes
Results (image right): Visualized in [Codea](http://codea.io)
Code here: https://github.com/brianolive/SubdivisionSurfaces

<img src="/images/subdivision.png" class="align-center" alt="">