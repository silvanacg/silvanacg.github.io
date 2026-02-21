---
title: "Predicting Post-Fire Debris Flows Using Atmospheric and Environmental Variables"
layout: single
author_profile: true
---

## Overview
Operational debris-flow hazard assessments often rely on rainfall thresholds and terrain susceptibility, but these approaches do not explicitly incorporate the atmospheric processes that generate hazardous rainfall.

This project develops a probabilistic model that integrates atmospheric conditions, storm characteristics, and landscape properties to determine most important drivers of debris-flow occurrence across wildfire burn areas in California.

---

## Research Questions
What are the most important drivers of post-fire debris flow occurrence?
Do atmospheric drivers and storm structure improve debris-flow prediction beyond traditional terrain-based susceptibility metrics?

---

## Data
- 268 storm cases (69 debris-flow events, 199 non-events)
- Radar reflectivity and precipitation characteristics
- Atmospheric predictors (moisture transport, instability indices, low-level winds)
- Terrain and burn severity variables
- Rainfall observations

---

## Model
A Random Forest classifier was trained to estimate debris-flow probability and evaluate predictor importance.

Model inputs were grouped into three categories:
- **Atmospheric conditions** — moisture transport, wind fields, convective instability
- **Storm properties** — rainfall intensity and radar reflectivity structure
- **Landscape susceptibility** — slope, burn severity, and terrain metrics

<div style="text-align:center; margin:20px 0;">
  <img src="/assets/workflow.png" style="max-width:700px; border-radius:12px;">
  <p style="font-size:0.9em; opacity:0.75;">
    Machine-learning framework combining atmospheric, storm, and terrain predictors
  </p>
</div>

---

## Key Findings

### Atmospheric drivers dominate prediction
Moisture transport, low-level winds, and radar reflectivity were consistently the most important predictors.

### Terrain alone is insufficient
Traditional susceptibility variables (slope, burn severity) provided weaker predictive skill when used without atmospheric context.

### Predictive performance
The model achieved strong discrimination between events and non-events (AUC ≈ 0.93).

### Operational implications
Applying the model to a real debris-flow event produced more spatially nuanced hazard estimates than rainfall-threshold approaches.

<div style="text-align:center; margin:20px 0;">
  <img src="/assets/model_probability.png" style="max-width:700px; border-radius:12px;">
  <p style="font-size:0.9em; opacity:0.75;">
    Example debris-flow probability output compared to traditional threshold methods
  </p>
</div>

---

**Outcome:** Research manuscript in preparation
