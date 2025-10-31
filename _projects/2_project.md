---
layout: page
title: Online Smooth Convex Optimization
description: Post-baccalaureate project
img: assets/img/monkey.jpg
importance: 3
category: work
---

Brain-decoder interfaces must choose which features are most important in decoding brain activity. Convex methods are limited in online optimization capabilities and often do not account for feature smoothness. This project develops an online, smooth convex optimization algorithm and validates its performance on simulated and recorded neural activity.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/features_comp.jpg" title="Selected neurons, ground truth vs convex-smooth vs lasso regression" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example of simulated neural activity and most relevant neurons vs batch (time). Ground truth, convex-smooth, and lasso regression are shown from left to right, respectively. Ground truth is smooth (features selected in one batch are likely to be selected in the next batch). Smooth-convex is also smooth, with some batches changing the selected features as more information is collected. Lasso regression is not smooth at all and selects a different set of neurons with every batch.
</div>
