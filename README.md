# Enhancing White Blood Cell Classification through GAN-based Data Augmentation

## Overview

White blood cell classification is pivotal for diagnosing blood-related diseases. Although deep learning models offer great promise for this task, limited labeled medical images impede their advancement. This project leverages Generative Adversarial Networks (GANs) to create synthetic blood cell images, enhancing classification performance when using CNN and CNN+RNN models. The approach is benchmarked against traditional image augmentation techniques and demonstrates an ensemble of GAN and traditional methods to achieve the best test accuracy of 87.77%.

## Methodology

### Stage 1: Baseline Establishment

A Deep CNN and CNN-RNN model is implemented to establish a baseline performance. The synergy of both architectures is exploited to better capture image features.

### Stage 2: Data Expansion

Two main apparoaches are used for data augmentation:
a. Traditional Augmentation techniques: Rotiation, translation, flipping
b. General Adversarial Networks (GANs) for synthetic white blood cell image generation

## Dataset

The project utilizes the [Blood Cell Count and Detection (BCCD) Dataset](https://www.kaggle.com/datasets/paultimothymooney/blood-cells). This dataset includes 373 images of white blood cells, categorized into four classes: Eosinophil, Lymphocyte, Monocyte, and Neutrophil. Basophils are not considered due to insufficient sample size.

## Ablation Study

An ablation study was conducted with the following configurations:
- Original Data Only
- Original Data + Traditionally Augmentated Data
- GAN-Augmented Data
- GAN-Augmented + Traditionally Augmentated Data

For an in-depth explanation and results, please refer to the [detailed report](your-report-link-here).
