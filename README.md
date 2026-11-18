# Spatial Analysis of Banking Deserts and Cash Infrastructure in Ireland

[![Project Status: Completed](https://img.shields.io/badge/Status-Completed-success.svg)]()
[![Institution: Maynooth University](https://img.shields.io/badge/Institution-Maynooth%20University-blue.svg)]()
[![Degree: MSc GIS / Geography (NCG616)](https://img.shields.io/badge/Dissertation-NCG616-orange.svg)]()

## Project Overview
This repository contains the code, data pipelines, and analytical documentation for my MSc dissertation at **Maynooth University (NCG616)**. 

The project investigates **banking deserts and cash infrastructure vulnerability** across the Republic of Ireland. By combining Census 2022 demographic datasets with spatial optimization models, this research identifies critical versus redundant bank, ATM, and credit union locations—with a specific focus on vulnerable populations such as the elderly and those with limited internet access.

---

## Key Methodologies & Tech Stack
* **Spatial Optimization:** Maximum Covering Location Problem (MCLP) modeling using Python (`spopt`, `geopandas`).
* **Routing & Accessibility:** Open Source Routing Machine (OSRM) for network-based travel time and distance matrices.
* **Demographic Vulnerability Index:** Census 2022 small-area statistics integration assessing digital exclusion and age dependency.
* **Data Visualization & Dashboarding:** Interactive Power BI dashboard communicating spatial gaps and policy recommendations.

---

## Repository Structure
```text
banking-deserts-ireland/
│
├── notebooks/               # Jupyter notebooks containing data processing and MCLP models
├── data/                    # Processed spatial layers and summary statistics 
├── outputs/                 # Exported maps, figures, and model evaluations
└── README.md                # Project documentation
