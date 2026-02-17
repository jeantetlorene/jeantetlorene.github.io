---
layout: page
title: Bioacoustics & Wildlife Monitoring
description: Improving deep learning acoustic classifiers with contextual information for automated wildlife monitoring, from bird songs to primate calls.
img: assets/img/project_bioacoustics.svg
importance: 2
category: Bioacoustics
related_publications: true
---

Passive acoustic monitoring (PAM) generates vast volumes of audio data that require automated analysis. We develop deep learning pipelines that leverage not only spectrograms but also contextual metadata — location, time of day, season — to significantly improve classification performance.

Our multi-branch CNN architecture integrates spatial and temporal metadata alongside spectrogram inputs, achieving substantial improvements in both bird song classification (22 species) and detection of the world's rarest primate, the Hainan gibbon.

### Key contributions
- Multi-branch CNN combining spectrograms with spatial/temporal metadata
- Geographical prior neural network for species distribution-aware classification
- 63% reduction in false positives for Hainan gibbon detection
- Integrated PAM pipeline for black-and-white ruffed lemurs in Madagascar
- Evaluation of generative models (VAEs, DDPMs) for bioacoustic data augmentation
