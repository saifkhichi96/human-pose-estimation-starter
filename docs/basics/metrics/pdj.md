---
title: PDJ
layout: default
parent: Metrics
grand_parent: Basics
nav_order: 3
---

# Percentage of Detected Joints (PDJ)
- Detected joint is considered correct if the distance between the predicted and the true joint is within a certain fraction of the torso diameter
- Alleviates the shorter limb problem since shorter limbs have smaller torsos
- PDJ at 0.2 → Distance between predicted and true join < 0.2 * torso diameter
- Typically used for 2D Pose Estimation
- Higher the better