---
layout: page
title: Federated Adversarial Training
description: Secure Federated Learning Framework for Medical Image Analysis
img: assets/img/federated_framework_1.png
importance: 4
category: research
related_publications: true
---

This project addresses the critical challenge of securing federated learning systems in medical imaging analysis, specifically focusing on chest X-ray interpretation using the CheXpert dataset. We developed a robust framework that maintains model performance while protecting against both white-box and black-box adversarial attacks.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/federated_framework_1.png" title="Federated Learning Framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture of our secure federated learning framework showing the interaction between local client training and global model aggregation with adversarial training components.
</div>

## Technical Approach

Our framework addresses several critical challenges in medical AI:
1. **Data Privacy**: Maintaining patient data confidentiality through federated learning
2. **Model Security**: Implementing adversarial training to protect against model poisoning
3. **Performance Optimization**: Balancing security measures with model accuracy

## Client-Specific Results

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/federated_training_client_1_result.jpg" title="Client 1 Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/federated_training_client_2_result.jpg" title="Client 2 Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Performance comparison across different client nodes showing model resilience against adversarial attacks while maintaining high accuracy in chest X-ray analysis.
</div>

## Key Innovations

1. **Adversarial Training Integration**
   - Implementation of both white-box and black-box attack simulations
   - Dynamic adjustment of adversarial training parameters
   - Robust defense mechanisms against model poisoning attempts

2. **Privacy-Preserving Features**
   - Secure aggregation of model updates
   - Local differential privacy implementation
   - Minimal data exposure during training

3. **Performance Optimization**
   - Balanced trade-off between security and model accuracy
   - Efficient communication protocol for model updates
   - Adaptive learning rate scheduling for faster convergence

## Impact and Applications

- Demonstrated successful protection against adversarial attacks while maintaining model performance
- Created a scalable framework applicable to various medical imaging scenarios
- Contributed to the development of secure, privacy-preserving medical AI systems
- Established best practices for implementing federated learning in healthcare settings

The project showcases the potential of secure federated learning in healthcare, particularly in scenarios where data privacy and model security are paramount.