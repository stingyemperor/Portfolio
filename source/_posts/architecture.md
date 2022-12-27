---
title: '03 - Architectural Sketch Recognition and Generation'
date: 2022-08-30
comments: false
---
#### Description

Digital drawing software like photoshop and clip studio paint lack convenient shadow references. Clip studio paint provides 3-D models with rendered shadows, but the amount of models available are very limited and does not allow for custom models. Thus, many  artists generally use a software like blender to help with obtaining references for shadows.  This is very inconvenient for users, as 3-D modelling programs are complicated to use.

The project aims to tackle this problem by providing users with an interface that can convert their 2-D drawings into 3-D models. These 3-D models can then be used to calculate shadows. While calculating shadows is mostly a closed problem now, 2-D sketch to 3-D models is still an active area of research. Recent papers in the area of sketch based modelling are combining machine learning with techniques from geometric modelling, but there is still work to be done with regards to finding a balance between usability and accuracy.

