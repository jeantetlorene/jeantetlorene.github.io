---
layout: page
title: Sea Turtle Behavior Classification
description: Deep learning approaches for automatic identification of underwater sea turtle behaviors using biologging sensors (accelerometers, gyroscopes, depth recorders).
img: assets/img/project_turtle_behavior.png
importance: 1
category: Wildlife Monitoring
related_publications: true
---

Sea turtles spend most of their lives underwater, making direct observation of their behavior extremely challenging. By deploying miniaturized multi-sensor loggers (accelerometers, gyroscopes, and time-depth recorders) on free-ranging turtles, we can record continuous movement data that encodes their behavioral repertoire.

Our work progressed from classical machine learning (Random Forest, CART) to fully convolutional neural networks (V-Net), achieving increasingly accurate automatic identification of behaviors including swimming, resting, feeding, and scratching — activities of crucial ecological importance that were previously impossible to monitor remotely.

### Key contributions
- First validation of accelerometer-based behavior identification in sea turtles
- Combined supervised learning approach (Random Forest + CART) for behavior discrimination
- Development of V-Net architecture adapted from biomedical image segmentation to 1D sensor data
- Automatic estimation of reproductive outputs (egg counts) from accelerometer data
