---
layout: page
title: Mathematical Modeling
description: SIR model with hospitalization and death
img: assets/img/4.jpg
importance: 1
category: work
related_publications: false
---

# SIR Model with Hospitalization and Death

## Overview
This project was part of my coursework in **Mathematical Modeling** and focused on extending the **Susceptible–Infected–Recovered (SIR) epidemiological model** by adding compartments for **hospitalization and death**.  
The goal was to capture the effects of hospitalization rates and healthcare capacity on disease progression and outcomes. Using **differential equations** and **numerical simulations in Python**, I analyzed how these factors influence infection peaks, recovery, and mortality.  

---

## Objectives
- To formulate a modified SIR model that incorporates hospitalization and death.  
- To simulate the disease progression under different hospitalization rates (h) and healthcare capacities (K).  
- To analyze the effect of healthcare system limitations on infection outcomes, recovery, and mortality.  

---

## Methodology
- **Model Formulation:** Extended the classic SIR model to include six compartments: Susceptible (S), Infected (I), Hospitalized (H), Not Hospitalized (NH), Recovered (R), and Death (D).  
- **Equations:** Developed a system of coupled differential equations describing transitions between these compartments.  
- **Simulation:** Implemented the model in **Python (NumPy, SciPy, Matplotlib)** for a population of N = 1000 individuals over 30 days.  
- **Parameters:** Varied hospitalization rate (h) and healthcare capacity (K) across nine cases in a 3×3 grid.  
- **Analysis:** Compared outbreak duration, infection peaks, recoveries, and mortality under different conditions.  
<!---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sir_diagram.jpg" title="Modified SIR Model Diagram" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sir_case_low.jpg" title="Case: Low h and K" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sir_case_high.jpg" title="Case: High h and K" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Compartmental diagram of the extended SIR model. Middle: Outbreak progression with low hospitalization rate and low healthcare capacity. Right: Outbreak progression with high hospitalization rate and high healthcare capacity.
</div>
--->
---

## Key Results
- **Hospitalization rate (h):** Increasing h significantly slowed outbreak progression, reduced mortality, and increased recoveries.  
- **Healthcare capacity (K):** While K influenced hospitalization trends, it had less impact than h in controlling outbreak duration and deaths.  
- **Low h, Low K:** Rapid outbreak (12–14 days), high mortality, susceptibles quickly depleted.  
- **High h, High K:** Gradual outbreak (>30 days), higher recoveries, mortality minimized, some susceptibles uninfected.  
- **Interpretation:** Optimizing hospitalization rates is crucial to reducing mortality and flattening the infection curve.  

---

## Skills Highlighted
- Compartmental modeling & differential equations.  
- **Python programming:** NumPy, SciPy (ODE solvers), Matplotlib for visualization.  
- Parameter variation & sensitivity analysis.  
- Data interpretation and scientific communication of model results.  
<!---
---

### Suggested Photos to Upload
- `assets/img/sir_model_cover.jpg` – cover/title slide of the project.  
- `assets/img/sir_diagram.jpg` – compartmental diagram of the modified SIR model.  
- `assets/img/sir_case_low.jpg` – outbreak progression graph --->

<!---
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}--->
