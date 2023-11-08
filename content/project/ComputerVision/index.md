---
title: 3D shape reconstruction
summary: Reconstruction of 3D facial geometry and head motion from 2D images.
tags:
  - Computer Vision
date: '2022-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: ''
#url_pdf: ''
#url_slides: ''
#url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
The aim of the project was to acquire a **3D face mesh and spatial head position** from input 2D video recordings and implement it in a **real-time** scenario. This was a pivotal component of a platform designed for creating autonomous digital people at *Soul Machines*. The project's implementation comprised the following steps, which were developed and seamlessly integrated into a single pipeline:

 - **Detection of facial marker points on the 2D images.**
 - **Creation of a parametric 3D model of a human head, featuring adjustable facial expressions.**
 - **Resolution of an optimization problem** involving parameters to project the 3D face onto the 2D image, resulting in corresponding facial expressions and head positions.
 - **Continuous tracking of all parameters over time**, accompanied by the application of filtering techniques to ensure smooth and realistic changes in facial expressions, head movements, and eyeball motions.

It is worth noting that this pipeline was specifically tailored for real-time use cases, facilitating the generation of a 3D reconstruction of the user's head and monitoring spatial changes in facial expressions.
