---
title: Multi-agent Rendezvous and Formation Control
date: 2024-04-23
summary: Cooperative control methods for rendezvous and formation control that guarantee agent connectedness throughout the maneuver.
preview_only: true
tags:
  - Cooperative Control
  - Multi-agent Systems
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

As a class project, I implemented [this paper](https://ieeexplore.ieee.org/document/4285848), which develops control laws for multi-agent rendezvous and formation control that guarantee the preservation of distance-based connectedness (i.e. communications radius). This project involved skills in:

- Cooperative control
- Consensus in multi-agent systems
- Multi-agent rendezvous and formation control
- Programming in Python

My implementation of these methods can be found [here](https://github.com/lshums16/Connectedness-with-Rendezvous-and-Formation-Control).

#### Naive Rendezvous

This example demonstrates a basic rendezvous algorithm that doesn't preserve connectedness, resulting in undesireable behavior.

![screen reader text](naive.gif)

#### Rendezvous with Guaranteed Connectedness:

This example demonstrates the rendezvous algorithm from the paper that guarantees connectedness throughout the maneuver.

![screen reader text](rendezvous.gif)

#### Formation Control

This example displays a very basic formation control example. More complicated examples are left to future work.

![screen reader text](formation_control.gif)






