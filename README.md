# 🗺️ Mapping the Data Landscape for Predictive Policing in Nairobi

### A Spatial-Temporal Exploratory Analysis and Methodological Framework

> **Author:** Kelvin Nkorisa Ntoonto  
> **Supervisor:** Dr. Paul Mutemi  
> **Institution:** The Open University of Kenya, School of Science and Technology  
> **Programme:** Master of Data Science (Reg. No: ST61/80165/2024)  
> **License:** MIT  
> **Status:** Thesis Repository — Accepted with Minor Corrections (October 2026)

---

## 📖 Overview

This repository contains the complete computational pipeline for the Master's thesis titled **"Mapping the Data Landscape for Predictive Policing in Nairobi: A Spatial-Temporal Exploratory Analysis and Methodological Framework."**

The study systematically audits Nairobi's publicly available crime data ecosystem (2018–2024) to determine whether it is technically and ethically ready for machine learning-based predictive policing. Rather than treating data scarcity as a barrier, this research treats the **data landscape itself as the primary object of analysis**.

### 🔑 Key Findings

- **Data is Missing Not At Random (MNAR):** Informal settlements (Mathare, Kibra, Mukuru) exhibit 20–40% data completeness vs. 65–95% in formal areas.
- **Severe Representational Disparity:** Demographic Parity Difference (DPD) = 0.504, vastly exceeding the 0.05 fairness threshold.
- **Spatial Clustering:** Global Moran's I = 0.34 (p < 0.01), with High-High clusters around the CBD (Starehe, Makadara).
- **Temporal Instability:** Sharp pandemic-era drop (5,844 cases in 2020) and structural surge (11,108 cases in 2023) violate stationarity assumptions.
- **Conclusion:** Nairobi's current public data ecosystem is **not ready** for defensible ML-based predictive policing.

---

## 🎯 Research Objectives

This pipeline maps directly to the five specific objectives of the thesis:

| # | Objective | Notebook / Script |
|---|-----------|-------------------|
| 1 | Map the data landscape & identify structural gaps | `notebooks/01_data_landscape_missingness.ipynb` |
| 2 | Conduct Exploratory Spatial-Temporal Analysis (ESTA) | `notebooks/02_spatial_temporal_diagnostics.ipynb` |
| 3 | Assess methodological robustness (MAUP, Small-N) | `notebooks/03_feature_stability_maup.ipynb` |
| 4 | Design transparent uncertainty-quantified visualizations | `notebooks/04_bayesian_uncertainty_surfaces.ipynb` |
| 5 | Audit representational equity (DPD/EOD metrics) | `notebooks/05_fairness_equity_audit.ipynb` |

---

## 📁 Repository Structure
