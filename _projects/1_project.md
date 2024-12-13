---
layout: page
title: SemGuS LENS
description: Leveraging Enumerative and LLM-Guided Synthesis for Semantic Program Generation
img: assets/img/lens_framework.jpg
importance: 1
category: research
related_publications: true
---

SemGuS LENS is a novel approach to program synthesis that combines the power of Large Language Models (LLMs) with traditional enumerative synthesis techniques. This project enhances the Semantics-Guided Synthesis (SemGuS) framework through an iterative, LLM-guided probabilistic enumeration approach.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lens_framework.jpg" title="SemGuS LENS Framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    High-level architecture of the SemGuS LENS framework showing the integration of LLM-guided synthesis with enumerative approaches.
</div>

## Key Innovations

Our framework introduces three major enhancements to the traditional SemGuS approach:

1. **LLM Integration**: We leverage large language models to generate high-quality candidate solutions.
2. **PCFG Support**: Extended support for Probabilistic Context-Free Grammars learned from LLM outputs.
3. **Enhanced Bottom-Up Enumeration**: Implementation of beam search with depth-aware pruning.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/llm_input.jpg" title="LLM Input Example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/llm_output.jpg" title="LLM Output Example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Example input prompt to the LLM for program synthesis. Right: Generated candidate solutions with associated probabilities.
</div>

## Experimental Results

Our experimental evaluation across SemGuS benchmarks demonstrates significant improvements in synthesis success rates compared to traditional approaches.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lens_results.jpg" title="Experimental Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparative analysis showing synthesis success rates and performance metrics across different benchmark categories.
</div>

## Technical Details

The system implements an iterative refinement loop where:
1. Failed synthesis attempts inform subsequent LLM queries
2. PCFG probabilities are progressively improved
3. Beam search optimizes the exploration of the solution space

Our evaluation highlighted interesting tradeoffs between domain-specific and general-purpose language models in candidate generation, providing valuable insights for future work in LLM-guided program synthesis.