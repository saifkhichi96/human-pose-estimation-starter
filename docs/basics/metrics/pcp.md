---
title: PCP
layout: default
parent: Metrics
grand_parent: Basics
nav_order: 2
---

# Percentage of Correct Parts (PCP)
- A limb is considered detected and a correct part if the distance between the two predicted joint locations and the true limb joint locations is at most half of the limb length (PCP at 0.5 )
- Measures detection rate of limbs
- Cons - penalizes shorter limbs
- __Calculation__
  - For a specific part, PCP = (No. of correct parts for entire dataset) / (No. of total parts for entire dataset)
  - Take a dataset with 10 images and 1 pose per image. Each pose has 8 parts - ( upper arm, lower arm, upper leg, lower leg ) x2
  - No of upper arms = 10 * 2 = 20
  - No of lower arms = 20
  - No of lower legs = No of upper legs = 20
  - If upper arm is detected correct for 17  out of the 20 upper arms i.e 17 ( 10 right arms and 7 left) → PCP = 17/20 = 85%
- Higher the better