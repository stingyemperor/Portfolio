---
title: '01 - Particle Based Simulation of Granular Material'
date: 2022-08-30
comments: false
---

### <span style="text-decoration:underline;">Introduction</span>

Simulation of granular material is challenging since the macroscopic behavior of the material is based upon the microscopic interaction between individual grains.A problem with the current simulation methods is that it is not possible to achieve interactive frame rates at higher particle counts. Thus for this project, a position based simulation is used based on the paper 'Unified Particle Physics'. 


#### <span style="text-decoration:underline;">Implementation</span>

The project is implemented in C++ utilizing the magnum library and OpenGL for rendering and intelTBB for multi-threading. Some examples of the simulation ruuning are as follows - 

1. Low Friction model


<iframe width="560" height="315" src="https://www.youtube.com/embed/7bcddxmZFZQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


2. High Friction Model

<iframe width="560" height="315" src="https://www.youtube.com/embed/nNgPC9vuZkM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


The code to the project can be found at [Code](https://github.com/stingyemperor/Granular-Material)