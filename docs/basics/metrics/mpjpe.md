---
title: MPJPE
layout: default
parent: Metrics
grand_parent: Basics
nav_order: 4
---

# Mean Per Joint Position Error (MPJPE)
- Per joint position error = Euclidean distance between ground truth and prediction for a joint
- Mean per joint position error = Mean of per joint position error for all k joints (Typically, k = 16)
- Calculated after aligning the root joints (typically the pelvis) of the estimated and groundtruth 3D pose.
- __PA MPJPE__
  - Procrustes analysis MPJPE.
  - MPJPE calculated after the estimated 3D pose is aligned to the groundtruth by the [Procrustes method](https://www.coursera.org/lecture/robotics-perception/pose-from-3d-point-correspondences-the-procrustes-problem-X22IH)
  - Procrustes method is simply a similarity transformation
- Lower the better
- Used for 3D Pose Estimation