<div align="center">

# Phase 2-1 — Adjustment Direction Prediction

### ICU Mechanical Ventilator Adjustment Direction Prediction Based on Multivariate Time-Series Analysis

<br>

A deep learning approach for predicting the direction of mechanical ventilator adjustment using multivariate ventilator time-series data.

<br>

[← Main Research Repository](https://github.com/hiimsharon/icu-ventilator-adjustment)

<br>

[Overview](#overview) ·
[Research Objective](#research-objective) ·
[Methodology](#methodology) ·
[Repository Structure](#repository-structure) ·
[Research Status](#research-status)

</div>

---

## Overview

Phase 2-1 represents the second decision stage of the proposed ICU mechanical ventilator adjustment framework.

This phase focuses on predicting the appropriate direction of ventilator adjustment based on multivariate ventilator-related time-series information.

The task is formulated as a multi-class classification problem to determine the adjustment direction after the requirement for ventilator adjustment has been identified.

---

## Research Objective

| Item | Description |
|---|---|
| Clinical Task | Ventilator adjustment direction prediction |
| Learning Task | Multi-class Classification |
| Input Data | Multivariate ventilator time-series data |
| Sequence Models | Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) |
| Hyperparameter Optimization | Bayesian Optimization with Tree-structured Parzen Estimator |
| Output | Adjustment direction prediction |

---

## Methodology

### Data Preparation

Multivariate ventilator records are processed into sequential samples according to the temporal characteristics of ICU ventilator management.

---

### Model Development

Deep learning sequence models, including LSTM and GRU, are developed to learn temporal patterns associated with ventilator adjustment decisions.

---

### Hyperparameter Optimization

Bayesian optimization based on the Tree-structured Parzen Estimator is applied to search suitable model configurations.

---

### Model Evaluation

Model performance is evaluated using classification metrics to assess the predictive performance of the adjustment direction prediction task.

---

## Repository Structure

```text
icu-ventilator-phase-2-1
|
├── README.md
├── assets/
└── documents/
```

---

## Research Status

Completed research phase.

The complete research workflow and final public materials will be updated according to research release planning.

---

## Notice

Clinical source data and patient-level information are not publicly distributed.

The materials provided in this repository are intended for academic reference and research communication only.

---

<div align="center">

<sub>

Copyright © 2026 Sha Huang. All Rights Reserved.

</sub>

</div>
