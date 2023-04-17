---
title: PCK
layout: default
parent: Metrics
grand_parent: Basics
nav_order: 1
---

# Percentage of Correct Keypoints (PCK)
- Detected joint is considered correct if the distance between the predicted and the true joint is within a certain threshold (threshold varies)
- PCKh@0.5 is when the threshold = 50% of the head bone link
- PCK@0.2 == Distance between predicted and true joint < 0.2 * torso diameter
- Sometimes 150 mm is taken as the threshold
- Head, shoulder, Elbow, Wrist, Hip, Knee, Ankle → Keypoints
- PCK is used for 2D and 3D (PCK3D)
- Higher the better