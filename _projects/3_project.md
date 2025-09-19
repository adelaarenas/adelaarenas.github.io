---
layout: page
title: SIR Model
description: SIR Model with Hospitalization and Death
img: assets/img/SIHRD_model.png
importance: 3
category: work
---

This project is from my Elementary Differential Equations course in undergrad, where I developed, using Python, an extended SIR model with hospitalization and death and evaluated how varying hospitalization rates and healthcare capacity influence outbreak progression, transmission dynamics, and overall mortality reduction.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIHRD_model.png" title="SIHRD_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Compartmental diagram of the modified SIR model with hospitalization and death.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIR_Model_Results.png" title="SIHRD Model Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Graphs of the outbreak progression in 160 days for S, I, H, R, and D compartments with varied α and K values.
</div>

You may view the full analysis in this paper: 