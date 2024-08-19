---
title: Decentralized WTA
date: 2024-04-23
summary: Cooperative control methods for the Weapon-Target Assignment (WTA) problem
preview_only: true
tags:
  - Cooperative Control
  - Weapon-Target Assignment
  - Decentralized
  - Communications Model

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

As a semester project, I implemented [this paper](https://arc.aiaa.org/doi/abs/10.2514/1.G001752), which explores different cost functions to facilitate cooperative control for the Weapon-Target Assignment problem when targets have different priority values and weapons have varying kill probabilities. The cost functions are:

- Traditional cost function
- Sufficiency Threshold cost function
- Enforced Tiering cost function
- Completion cost function

Each cost function prioritizes targets in different ways in order to maximize the probability of achieving a desired outcome (i.e. most targets destroyed, highest priority targets destroyed, etc.), and the method is decentralized as each weapon maintains a current estimate of the assignment state based on the latest information it has receeived from other weapons according to the communications model outlined in the paper. My implementation of the various cost functions and simulation results can be found [here](https://github.com/lshums16/multiagent_WTA). Ths project involved skills in:

- Cooperative control
- Multi-agent systems
- Optimization
- Programming in Python

The following figures demonstrate examples of each cost function implemented in simulation. The orange dots represent weapons, and the multi-colored dots represent targets of different priority levels (blue being the highest and red being the lowest). The connecting lines between a weapon and target represent the current assignment.

#### Traditional cost function:

![screen reader text](trad.gif)

#### Sufficiency Threshold cost function:

![screen reader text](st.gif)

#### Enforced Tiering cost function:

![screen reader text](tiered.gif)

#### Completion cost function:

![screen reader text](completion.gif)




