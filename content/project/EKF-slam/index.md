---
title: Square Root SAM
date: 2023-12-23
summary: Factor graph-based offline SLAM method
preview_only: true
tags:
  - SLAM
  - Factor graphs
  - State estimation
  - Mobile Robotics
  - Data Association

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

As part of a class project, I implemented an online, EKF-based SLAM algorithm in a simulated robot soccer environment as well as on the Victoria Park dataset. This method estimates both the current state of a mobile robot and the locations of stationary landmarks based on noisy sensor data and imperfect motion commands.

To maintain academic integrity, my implementation of this method is kept private in a Github repository. This project involved skills in:

- State estimation
- SLAM
- Data Association
- Dynamics Systems
- Python

The following figures show the performance of the SLAM algorithm for robot soccer (top) and the Victoria Park dataset (bottom). In both cases, data association algorithms were run to associate measurements with known/new landmarks.

![screen reader text](featured.gif)

![screen reader text](video_task2.gif)