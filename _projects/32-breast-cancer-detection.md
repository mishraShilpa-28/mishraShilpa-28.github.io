---
layout: page
title: "Breast Cancer Detection (CNN)"
description: "Convolutional neural network that classifies breast biopsy images."
importance: 32
category: ai and data
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/breast-cancer-detection) · **Tech:** Python, TensorFlow, Keras

## The problem

Reading stained biopsy images is slow and specialists can disagree. Computer-aided diagnosis can support them.

## What it does

- **Four-class** (normal, benign, in-situ, invasive) and **binary** (carcinoma or not) classification.
- **Multi-scale CNN** that looks at both cell-level detail and tissue structure.
- **Test on your own image** with the trained model.

## What I learned

- How CNNs learn image features, and why patch size and scale matter for medical images.
- Preprocessing large images and avoiding data leakage between training and test sets.
