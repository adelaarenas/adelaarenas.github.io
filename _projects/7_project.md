---
layout: page
title: Mathematical Modeling
description: SIR model with hospitalization and death
img: assets/img/4.jpg
importance: 1
category: work
related_publications: false
---

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
