---
title: "Storm Structure and Reflectivity Patterns in Precipitation Systems Associated with Post-Fire Debris-Flow Storms"
layout: single
author_profile: true
---

## Overview
Post-fire debris flows in California are commonly triggered by short-duration, high-intensity rainfall.  
However, rain gauges provide only point measurements and often miss how rainfall evolves across an entire burned landscape.

This project investigates how structure of precipitation systems and reflectivity in burned areas evolves during debris-flow-producing storms by tracking precipitation systems using weather radar data.

---

## Data
- NEXRAD radar reflectivity mosaics (5-minute resolution)
- Inventory of 67 post-fire debris flows (2014–2022)
- Nearby rain gauge observations
- Fire perimeter datasets

---

## Method
I adapted a spatial correlation tracking algorithm to identify and follow coherent precipitation systems intersecting burned areas.

The method tracks storm evolution through time and extracts structural properties:

- area (storm size)
- propagation speed and direction
- eccentricity (storm shape)
- reflectivity distribution within burn scars

<div style="text-align:center; margin:20px 0;">
  <img src="/assets/Fig2.png" style="max-width:700px; border-radius:12px;">
  <p style="font-size:0.9em; opacity:0.75;">
    Workflow for tracking algorithm
  </p>
</div>

---

## Key Findings

### Seasonal storm behavior
- **Winter storms:** large, fast-moving, elongated systems producing widespread moderate rainfall
- **Summer storms:** small, slow convective systems producing localized intense rainfall bursts

### Timing insight
Maximum radar reflectivity over burn scars aligned more consistently with peak short-duration rainfall than traditional reflectivity-threshold methods.

<div style="text-align:center; margin:20px 0;">
  <img src="/assets/Abstract_Image.png" style="max-width:700px; border-radius:12px;">
  <p style="font-size:0.9em; opacity:0.75;">
    Contrasting precipitation systems and reflectivity during debris-flow events
  </p>
</div>

---
