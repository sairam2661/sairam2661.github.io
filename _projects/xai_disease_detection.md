---
layout: page
title: Explainable AI Framework
description: XAI-Based Disease Detection in Paddy Crops using Auto-ML and LIME
img: assets/img/xai_framework.png
importance: 2
category: work
related_publications: true
---

This project develops an explainable AI framework for detecting diseases in paddy crops, combining the power of Auto-ML optimization with LIME-based interpretability. Our approach achieved significant improvements in both detection accuracy and model transparency.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/xai_framework.png" title="XAI Framework Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overall architecture of our XAI framework showing the integration of Auto-ML optimization with LIME-based interpretability components.
</div>

## Technical Approach

Our framework utilizes several cutting-edge techniques:
1. **Auto-ML Optimization**: Using Optuna and Ray Tune for distributed hyperparameter optimization
2. **Transfer Learning**: Leveraging EfficientNet and Vision Transformers
3. **Interpretability**: LIME-based explanation generation for model decisions

## Analysis Pipeline

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sample_xai_input_1.png" title="Input Image 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/heatmap_lime_intermediate_1.png" title="LIME Heatmap 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sample_xai_output_1.png" title="Final Explanation 1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Case study 1: Original paddy crop image (left), intermediate LIME heatmap visualization (middle), and final explainable output highlighting disease-affected regions (right).
</div>


## Key Achievements
- 94% detection accuracy across multiple disease categories
- 40% reduction in model training time through Auto-ML optimization
- 6% improvement over traditional CNN approaches
- Project of the Year Award at PSG Tech
- Enhanced interpretability through multi-stage LIME visualization pipeline

The visualization pipeline demonstrates our framework's ability to not only detect diseases but also provide comprehensive explanations through intermediate heatmaps and final region highlighting, making the AI decision-making process transparent to agricultural experts.