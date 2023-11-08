---
title: Avatar animation technologies
summary: Avatar 3D animation engine for driving real-time avatar-user interaction.
tags:
  - Animation Technologies
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

I had the opportunity to collaborate with a highly talented team at *Soul Machines*, a multi-award-winning startup, on a series of projects aimed at creating **hyper-realistic 3D digital avatars**. These avatars were designed to operate in **real-time**, exhibiting human-like behaviors, understanding users' emotional states and intents, and responding both verbally and through appropriate gesturing, facial expressions, and eye motions. This endeavor involved the development of various components of animation technologies, integrated into a custom-built animation engine that drove facial and full-body motions. The primary challenge was ensuring real-time user interaction, resulting in the development of a tech stack for autonomously animated digital humans. Below, I present a list of projects related to the animation and visual aspects of the developed technologies that I was a part of:

 - ***Facial animation using a non-linear blendshape model***. To infuse more realism into facial motion, the classical linear blendshape model was extended by incorporating intermediate shapes, enabling smoother transitions and artistically defined paths. This led to richer facial expressions and subtle lip movements synchronized with speech.

 - ***Full-body animation blending system***. We established a system for real-time manipulation of the full-body skeleton by blending various inputs for animation parameters. This allowed us to generate a cohesive output from multiple simultaneous and continuous inputs, resulting in meaningful and realistic gesturing.

 - ***Arm reaching system***. Our system enabled the avatar to produce transitioning animations with arm-pointing-like behaviors, reaching for objects of interest in the surrounding 3D space. These animations were real-time, smooth, realistic, and could be stylized to suit different contexts.

 - ***Eye gazing system***. This system controlled eye motions and gaze direction based on the avatar's state, such as maintaining eye contact while conversing with a user, blinking behavior, and focusing on points of interest, mimicking real-life behaviors.

Additionally, we developed a system to **synchronize animations with text and voice**, integrated with a rendering engine. You can explore real-life avatar demos by following the links below.

https://www.youtube.com/watch?v=27UiAo3OyeE
https://www.youtube.com/watch?v=rjclQ3m5JRw



