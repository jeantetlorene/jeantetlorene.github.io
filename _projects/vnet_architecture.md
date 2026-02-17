---
layout: page
title: V-Net for Animal Behavior
description: Adapting the V-Net fully convolutional neural network from biomedical image segmentation to temporal sensor data for animal behavior classification.
img: assets/img/project_vnet.png
importance: 4
category: Wildlife Monitoring
related_publications: true
---

The V-Net is a fully convolutional neural network originally designed for 3D biomedical image segmentation. We adapted this architecture for 1D temporal data from animal-borne sensors, creating a powerful tool for behavior classification that can process continuous streams of accelerometer and gyroscope data.

Our adapted V-Net achieves an AUC score of 88% for predicting six behavioral categories in green turtles, and has since been successfully applied to chinstrap penguin prey capture detection and other species.

### Key contributions
- Novel adaptation of V-Net from 3D image to 1D temporal signal processing
- 88% AUC for six-class behavior prediction in green turtles
- Application to chinstrap penguin prey capture quantification
- Open-source implementation for the ecology community
