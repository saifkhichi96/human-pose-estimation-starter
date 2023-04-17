---
title: Basics
layout: default
nav_order: 2
has_children: true
---

# Basics of Human Pose Estimation

- Defined as the problem of localization of human joints (or) keypoints
- A rigid body consists of joints and rigid parts. A body with strong articulation is a body with strong contortion.
- Pose Estimation is the search for a specific pose in space of all articulated poses
- Number of keypoints varies with dataset -  LSP has 14, MPII has 16, 16 are used in Human3.6m
- Classifed into 2D  and 3D Pose Estimation
  - __2D Pose Estimation__
  - Estimate a 2D pose (x,y) coordinates for each joint in pixel space from a RGB image
  - __3D Pose Estimation__
  - Estimate a 3D pose (x,y,z) coordinates in metric space from a RGB image, or in previous works, data from a RGB-D sensor.    (However, research in the past few years is heavily focussed on generating 3D poses from 2D images / 2D videos)

If you want a slightly more rigorous tutorial and understand the basics of Human Pose Estimation and how the field has evolved, check out these articles on [2D Pose Estimation](https://blog.nanonets.com/human-pose-estimation-2d-guide/?utm_source=github&utm_medium=social&utm_campaign=pose&utm_content=cbsudux) and [3D Pose Estimation](https://blog.nanonets.com/human-pose-estimation-3d-guide/). This [presentation by Wei Yang](https://www.slideshare.net/plutoyang/mmlab-seminar-2016-deep-learning-for-human-pose-estimation) also provides an informative roadmap on 2D Human Pose Estimation research.
