---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Autonomous Satellite Inspection and GNC Architectures

Designed Guidance, Navigation, and Control (GNC) architectures and trajectory optimization frameworks for the [AFRL Safe Trusted Autonomy for Responsible Spacecraft (STARS)](https://afresearchlab.com/wp-content/uploads/2024/03/AFRL_STARS_FS_240318.1.pdf) program. The project ensured robust orbital inspection and information maximization under illumination, occlusion, Field-of-View (FOV), and visibility constraints. I developed a memory-based switched observer that daisy-chains distance estimates for relative navigation in GPS-denied environments, addressing features entering and exiting the camera's FOV. I formulated a constrained optimal control problem using a Hamilton-Jacobi-Bellman (HJB) approach, integrating robustified barrier functions to enforce collision avoidance and keep-in zones. Algorithmic performance was validated through simulations, as detailed in my publications at the American Control Conference (ACC) [[Paper]](https://ieeexplore.ieee.org/abstract/document/11108034) and my submission to IEEE Transactions on Aerospace and Electronic Systems (TAES) [[Preprint]](https://arxiv.org/abs/2504.15954). [[Slides]](/files/satellite_inspection.pdf)


## Gaussian Process-Based Error Correction for Robotic Field Mapping

<iframe width="560" height="315" src="https://www.youtube.com/embed/CKP7FaPYd3Y" title="Experimental Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Applied Gaussian Process-based error correction techniques tailored for autonomous robotic field mapping applications. This approach improved overall localization accuracy by effectively fusing extended Kalman filter (EKF) estimates with underlying spatial priors. The methodology was further extended to include scalar field mapping frameworks equipped with adaptive high-intensity region avoidance mechanisms. [[Experimental Video]](https://www.youtube.com/watch?v=CKP7FaPYd3Y)

## Event-Triggered CBFs for Safety-Critical Obstacle Avoidance

Developed an event-triggered hybrid feedback control model to robustly resolve suboptimal Control Barrier Function Quadratic Programs (CBF-QPs). This approach tightens safety constraints to account for finite computation times and strictly bounds safety deviations in autonomous systems. I designed these safety-critical controllers to enforce state constraints and collision avoidance in real-time. The obstacle avoidance algorithms were rigorously validated through actual ROS 2 experiments on physical robots, ensuring forward invariance during real-time deployment on holonomic turtlebot.
[[Code]](https://github.com/Tochukwu1/cbf_event_pkg)

## Ambient Sound Classification using CNNs

Developed and trained a 2D Convolutional Neural Network (CNN) to classify 5-second audio clips into five distinct ambient environment categories: indoor quiet, street traffic, kitchen activity, human chatter, and nature. The processing pipeline transforms raw 48 kHz audio into 128-bin log-mel spectrograms, which are then treated as single-channel images. These images are fed into a four-layer CNN architecture that utilizes max-pooling, dropout regularization, and adaptive average pooling before passing through a fully connected classifier. The model was trained end-to-end using negative log-likelihood loss and the Adam optimizer. To improve robustness, I implemented a comprehensive data augmentation pipeline including pitch shifting, time-stretching, noise injection, time rolling, and frequency masking. This augmentation strategy significantly improved generalization, allowing the model to achieve a 98.76% weighted F1 score without increasing the underlying model size. [[Poster]](/files/EEL5840_Poster.pdf