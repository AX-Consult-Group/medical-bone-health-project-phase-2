# Bone Health Project
# Phase 2 – Clinical & Commercial Simulation

This repository contains a public, reproducible analysis extending Phase 1 findings to simulate the **clinical and commercial impact** of improved osteoporosis screening and treatment. Using simulated, literature-aligned data, the analysis focuses on modeling outcomes for high-risk individuals—especially those missed under current screening criteria—and estimating downstream commercial potential for a hypothetical therapy, **OsteoGuard**.

<img width="1020" height="680" alt="Design Overview Graphic - Phase 2" src="https://github.com/user-attachments/assets/d88c9ec7-bcb4-431b-80a0-e2f5c32d7776" />


---

## What this analysis shows

- Simulated **clinical outcomes** for high-risk individuals receiving OsteoGuard vs control  
- Impact of ** treatment initiation** on bone density and fracture reduction  
- **Adherence and discontinuation patterns** in a simulated real-world population  
- **Commercial outcomes**, including addressable population size, market capture, revenue, and profitability  
- KPI dashboards integrating **clinical and commercial metrics** for executive-level decision support  

---

## Key concepts

Phase 2 builds directly on Phase 1 population segments:

1. **Screening-eligible individuals** (based on age and sex criteria)  
2. **High bone-health risk individuals** (based on DXA T-scores and risk proxies)  
3. **Missed high-risk individuals**, who form the **primary simulated treatment population**  

The primary objective is to demonstrate how **capturing and treating missed high-risk individuals** can improve clinical outcomes and generate measurable commercial value.

---

## Data sources

Phase 2 uses simulated datasets based on:

- **Phase 1 population segments and prevalence rates**  
- **Published clinical literature** for osteoporosis treatment effects  
- **Market and commercial assumptions** aligned with realistic uptake, adherence, and pricing  

All simulated datasets are generated within the repository for reproducibility.

---

## Methods (high level)

- Populations from Phase 1 were used to define treatment cohorts  
- Simulated OsteoGuard therapy models:
  - **Lumbar spine BMD improvement**
  - **Fracture reduction**
  - **Adherence & discontinuation** over 24 months  
- Commercial modeling estimates:
  - **Addressable high-risk population**
  - **Market capture under improved screening**
  - **Revenue and profitability scenarios**  
- KPI dashboards summarize **population, clinical, and commercial outcomes**  
- All parameters are literature-aligned and grounded in **realistic industry assumptions**

---

## Important notes

- This analysis uses **simulated data**, not real patient data  
- Clinical outcomes are **illustrative** and not intended for medical decisions  
- Commercial assumptions are **hypothetical** and meant for strategy demonstration  
- Minor differences from published clinical or market data may exist due to simulation choices  

---

## How to view the report

The full rendered report will be available via **GitHub Pages**:

https://ax-consult-group.github.io/medical-bone-health-project-phase-2/poe_bone_health_phase_2.html

---

## R packages used

The analysis was conducted in R using the following packages:

- **Data manipulation & pipelines**  
  - magrittr  
  - tidyverse  
  - dplyr  
  - tibble  
  - janitor  
  - tidyr  
  - patchwork  

- **Data import & export**  
  - haven  
  - readxl  
  - writexl  

- **Analysis & utilities**  
  - psych  
  - scales  
  - zoo  

- **Visualisation & reporting**  
  - ggplot2  
  - ggrepel  
  - knitr  
  - kableExtra  

RStudio 2026.01.0+392 "Apple Blossom" Release (49fbea7a09a468fc4d1993ca376fd5b971cb58e3, 2026-01-04) for Windows  
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) RStudio/2026.01.0+392 Chrome/140.0.7339.249 Electron/38.7.2 Safari/537.36, Quarto 1.8.25
