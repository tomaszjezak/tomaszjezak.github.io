---
layout: page
title: Safety-Critical, Multi-Modal ML Pipeline and Dataset
description: Large-scale ML pipeline and human detection dataset at Amazon Robotics
img: assets/img/ml-pipeline.jpeg
importance: 1
category: research
---

## Overview

Engineered an end-to-end **ML pipeline processing 500GB+/day** at Amazon Robotics, enabling safe human-robot interaction in warehouse environments.

## Key Contributions

### ML Pipeline Architecture
- Built complete pipeline: **record → preprocess → label → train → evaluate**
- Automated workflow using **AWS** stack:
  - S3 for storage
  - ECS & Lambda for compute
  - EventBridge for orchestration
  - Batch & SageMaker for training
- Integrated **MLFlow** for experiment tracking and model versioning

### Multi-Modal Human Detection Dataset
- Created massive dataset: **1.5M images, 500+ hours of video**
- Multi-modal sensors: **RGB, thermal, depth, radar, time-of-flight**
- Designed for **safe human-robot interaction** in dynamic warehouse settings

### Automated Data Collection System
- Architected **7 five-sensor rigs** deployed across varied warehouse environments
- Built on **ROS2** for synchronized multi-sensor capture
- Captured diverse, multimodal human activity data at scale

### Model Benchmarking
- Evaluated **segmentation** and **detection models** (SAM2, Detectron2)
- Benchmarked performance across RGB and thermal modalities

## Technical Stack

`Python` `AWS (S3, ECS, Lambda, EventBridge, Batch, SageMaker)` `MLFlow` `ROS2` `PyTorch` `SAM2` `Detectron2`

