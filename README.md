# ICU Patient Monitor Energy Analysis

Analysis code accompanying the thesis:

**The Hidden Environmental Cost of Patient Monitoring:
Exploring Energy Waste and Data-Driven Solutions in Intensive Care**

Dinos Kritsis  
Utrecht University / Institute for Risk Assessment Sciences (IRAS)  
In collaboration with Philips

## Overview

This repository contains the code used to analyse ICU monitoring activity,
estimate monitor energy consumption, identify idle-time patient profiles,
simulate low-power scenarios, and evaluate admission-time prediction.

The analysis uses two publicly available clinical research databases:

- MIMIC-IV
- eICU Collaborative Research Database

## Repository contents

The code covers:

1. Data cleaning and activity-timeline construction
2. Active/idle hour classification
3. Energy and CO2 calculations
4. K-means clustering
5. Rule-based low-power simulations
6. Random Forest prediction with SMOTE
7. Alarm and mortality analyses
8. Temporal and national scaling analyses
9. Figure generation

## Data availability

The underlying MIMIC-IV and eICU data are not included in this repository.

Access to these datasets is governed by PhysioNet's respective data-use
requirements. Users wishing to reproduce the analysis must obtain access
directly through PhysioNet.

## Software

The analyses were conducted primarily in Python using packages including
pandas, NumPy, scikit-learn, imbalanced-learn, matplotlib and scipy.

## Citation

If using this repository in connection with the thesis, please cite:

Kritsis, D. (2026). The Hidden Environmental Cost of Patient Monitoring:
Exploring Energy Waste and Data-Driven Solutions in Intensive Care.
Utrecht University.
