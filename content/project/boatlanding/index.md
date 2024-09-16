---
title: Precision Maritime Localization and Landing
date: 2023-04-23
summary: Estimation and control to land a drone autonomously on a small raft.
preview_only: true
tags:
  - State Estimation
  - Extended Kalman Filter
  - Control Systems 
  - Python
  - C++
  - ROS

# Cover image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 2
  focal_point: 'Center'
  preview_only: false
  # filename: my-image.jpg  # Uncomment to load an image from `assets/media/` instead.
---

For this project, I worked with a graduate student on his master’s thesis to develop a control system that lands an autonomous drone on a boat. This was done using both Real-time Kinematic (RTK) positioning and AprilTag positioning that worked simultaneously to locate the rover in relation to the boat using an Extended Kalman Filter. We successfully landed the drone within our desired accuracy using each localization method in isolation and working simultaneously. I have also designed software architecture to interface the drone’s and boat’s sensors for ROS and ROS2 environments. Other responsibilities included executing flight tests in outdoor and indoor environments, maintaining hardware, and translating programs that run in a ROS environment to run in ROS2.

{{< video src="flight.mp4" controls="yes" >}}

This project involved skills in:
- State estimation
- Control Systems
- ROS2
- Python
- C++
- PX4
- Mechatronics
