---
layout: page
title: The Cancel Culture 🛵
description: Predicting Rider Cancellations in Food Delivery (Runner-up @ Cascade Cup)
img: assets/img/delivered_cancelled_daily.png
importance: 2
category: fun
related_publications: false
---

🏆 Runner-up at Cascade Cup Competition!

Ever wondered why your food delivery gets cancelled? We did too! Here's how we dove into Shadowfax's delivery data to uncover the mysteries behind rider cancellations.

## The Mystery Unfolds 🔍

What makes a delivery rider cancel an order? Is it the distance? The time? Or maybe they're just having a bad Saturday? We analyzed thousands of delivery records to find out!

### The Tale of Two Orders
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/delivered_cancelled_daily.png" title="Daily Order Patterns" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Daily patterns of delivered vs cancelled orders. Spot the suspicious Saturday spike! (January 30th had some explaining to do...)
</div>

### The Day in the Life
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hourly_sessions.png" title="Hourly Patterns" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hourly breakdown of orders showing the classic "small spike, big spike, sleep" pattern. Even delivery riders need their beauty sleep!
</div>

## The Plot Thickens 📊

### The Experience Factor
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lifetime_orders.png" title="Lifetime Orders Impact" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Turns out, experienced riders cancel less! Who would've thought? 🤔
</div>

### The Distance Dilemma
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/distance_analysis.png" title="Distance Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The longer the distance, the higher the chance of cancellation. Physics wasn't lying about that distance-effort relationship!
</div>

## What We Discovered 🧪

Some fascinating (and sometimes obvious) insights:
- Saturdays are the cancellation champions (maybe riders have weekend plans too!)
- Most cancellations happen during lunch hours (hangry riders?)
- Experienced riders are more reliable (practice makes perfect!)
- Long-distance relationships... err... deliveries are more likely to fail
- No orders during the night (even riders need their sleep!)

## Technical Bits 🤓

For the data nerds out there:
- Performed time-series analysis on order patterns
- Used highlight tables for session time analysis
- Created multi-dimensional visualizations for pattern recognition
- Implemented predictive models for cancellation probability
- Analyzed correlations between various factors affecting cancellations

## Impact 🎯

Our analysis helped Shadowfax:
- Better predict potential cancellations
- Optimize rider assignments based on experience
- Understand peak cancellation periods
- Improve overall delivery success rates

Who knew food delivery data could tell such interesting stories? This project won us the runner-up position at Cascade Cup, proving that sometimes the most interesting insights come from everyday data! 

Remember: Behind every cancelled order is a story... and probably a hungry customer! 🍕