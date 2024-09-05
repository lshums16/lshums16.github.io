---
title: EKF-based SLAM
date: 2023-11-23
summary: EKF-based SLAM algorithm with unknown data association
preview_only: true
tags:
  - SLAM
  - EKF
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

As a semester project, another student and I implemented [this paper](https://journals.sagepub.com/doi/abs/10.1177/0278364906072768?casa_token=pN7fAOwwlNkAAAAA:xKHvBlwOmA85TjnqGrDAXJuP4rMFblq04_ujgPm3OZN5w3V_GW1w1iO37ldpOapQezLfnxLLRWhfzTk), which develops an offline, factor graph-based SLAM algorithm called Square Root SAM. This method estimates both the state of a mobile robot over time and the locations of stationary landmarks based on noisy sensor data and imperfect motion commands.


To maintain academic integrity, my implementation of this method is kept private in a Github repository. This project involved skills in:

- State estimation
- SLAM
- Probability theory
- Data Association
- Dynamics Systems
- Python

The following figures show the performance of Square Root SAM (top) over an EKF-based SLAM method (bottom). Both algorithms were run offline on the same data set. One benefit of the offline Square Root SAM method over the online EKF-based algorithm is that it can use future sensor data and data association to estimate the entire history of the robot's trajectory.

![screen reader text](featured.png)

![screen reader text](EKF-final-graph.png)
