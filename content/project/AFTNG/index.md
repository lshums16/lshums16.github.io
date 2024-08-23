---
title: Adaptive Finite-Time Guidance Law
date: 2024-04-23
summary: Adaptive finite time guidance law for pursuer tracking an accelerating target.
preview_only: true
tags:
  - Nonlinear Control
  - Adaptive Finite-Time Control
  - Proportional Navigation
  - GNC
  - Python

# Cover image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 2
  focal_point: 'Center'
  preview_only: true
  # filename: my-image.jpg  # Uncomment to load an image from `assets/media/` instead.
---

![screen reader text](featured.gif)

As a semester project, I implemented [this paper](https://arc.aiaa.org/doi/abs/10.2514/1.G007664), which derives and evaluates the performance of three guidance laws for a pursuer tracking an accelerating target. The guidance laws are:

- ProNav (PNG)
- Finite time convergence guidance (FTCG)
- Adaptive finite time nonlinear guidance (AFTNG)

My implementation of the three guidance laws can be found [here](https://github.com/lshums16/adaptive-pursuer-guidance-law). This project involved skills in:
- Nonlinear control
- Adaptive control
- Lyapunov stability analysis
- Python

As shown in the GIF above, all three guidance laws successfully hit the target, but they do so at different times. Further analysis showed that more extreme acceleration profiles of the target resulted in higher success for FTCG and AFTNG in comparison with PNG. 

