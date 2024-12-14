---
layout: page
title: Edge-Based Deep Learning
description: Real-Time Road Damage Detection using Edge Computing
img: assets/img/edge_framework.png
importance: 3
category: work
related_publications: false
---

This project implements an efficient edge computing framework for real-time road damage detection, optimizing deep neural networks for deployment on resource-constrained devices like Raspberry Pi.

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/edge_framework.png" title="Edge Computing Framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture of our edge computing framework showing the optimization pipeline for deep neural network deployment.
</div>

## Real-Time Detection Results

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sample_edge_output_1.png" title="Detection Result 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sample_edge_output_2.png" title="Detection Result 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample detection results showing real-time road damage identification with bounding boxes and confidence scores across different road conditions and damage types.
</div>

## Live Demo

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/edge_sample_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Live demonstration of our edge computing framework performing real-time road damage detection on a Raspberry Pi device.
</div>

## Technical Implementation

The framework focuses on three key aspects:
1. **Model Optimization**: ONNX-based model compression and optimization
2. **Edge Deployment**: Efficient deployment on Raspberry Pi hardware
3. **Real-Time Processing**: Optimized inference pipeline for minimal latency

## Key Achievements
- 15% reduction in inference latency
- F1 score of 0.64 on the RDD2020 dataset
- 10-second improvement in critical response time
- Successful deployment on resource-constrained edge devices
- IIIT Data Mobility Fellowship award

The framework demonstrates the viability of deploying complex deep learning models on edge devices for real-time applications, particularly in infrastructure maintenance and safety monitoring contexts.