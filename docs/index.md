---
title: Human Pose Estimation in PyTorch
layout: home
---

A PyTorch-based starter kit for 2D human pose estimation projects, designed for researchers working on optimizing human pose estimation networks using knowledge distillation and neural architecture search. It provides an interface for training, inference, and evaluation, as well as the dataloaders for common human pose estimation datasets.

![screenshot](assets/images/screenshot.png)

For a more comprehensive understanding of human pose estimation, including 2D and 3D pose estimation basics, loss functions, evaluation metrics, and applications, please refer to the [introduction here](basics.md).

This repository is a fork of [PyTorch-Pose](https://github.com/bearpaw/pytorch-pose), and also uses code from several other repositories as listed in the [Acknowledgments](#acknowledgments) section.

## Table of Contents
- [Getting Started](#getting-started)
  - [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Structure](#structure)
- [Supported Models](#supported-models)
- [Supported Datasets](#supported-datasets)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Getting Started
These instructions will help you set up the project on your local machine for development and testing purposes.

### Features
- Multi-thread data loading
- Multi-GPU training
- Logger
- Training/testing results visualization

See the [installation guide](installation.md) for instructions on how to set up the project on your local machine, and [Getting Started](getting-started.md) for a quick start guide on how to train and evaluate a model. A [curated list of optimzation resources](optimization.md) is also provided to help you get started with knowledge distillation and neural architecture search.

## Supported Models
The following models are supported:
- [x] Alejandro Newell, Kaiyu Yang, and Jia Deng, Stacked Hourglass Networks for Human Pose Estimation, [arXiv:1603.06937](http://arxiv.org/abs/1603.06937), 2016. ([GitHub](https://github.com/princeton-vl/pose-hg-train))
- [x] Xiao et al., Simple Baselines for Human Pose Estimation and Tracking, [arxiv:1804.06208](https://arxiv.org/abs/1804.06208), ECCV 2018 ([GitHub](https://github.com/Microsoft/human-pose-estimation.pytorch))

For more information on the models, please refer to the [models documentation](models.md).

## Supported Datasets
Dataloaders for the following datasets are provided:
- [x] [COCO](http://cocodataset.org/#keypoints-challenge2017)
- [x] [MPII](http://human-pose.mpi-inf.mpg.de)
- [x] [Leeds Sports Pose (LSP)](http://sam.johnson.io/research/lsp.html)

For more information on the datasets, please refer to the [datasets documentation](datasets.md).

## Acknowledgments
- [Human-Pose-Estimation-101](https://github.com/cbsudux/Human-Pose-Estimation)
- [PyTorch-Pose](https://github.com/bearpaw/pytorch-pose)
