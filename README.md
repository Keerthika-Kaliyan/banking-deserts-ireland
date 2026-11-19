# Spatial Analysis of Banking Deserts and Cash Infrastructure in Ireland

[![Project Status: Completed](https://img.shields.io/badge/Status-Completed-success.svg)]()
[![Institution: Maynooth University](https://img.shields.io/badge/Institution-Maynooth%20University-blue.svg)]()
[![Degree: MSc GIS / Geography (NCG616)](https://img.shields.io/badge/Dissertation-NCG616-orange.svg)]()

## Project Overview
This repository contains the code, data pipelines, and analytical documentation for my MSc dissertation at **Maynooth University (NCG616)**. 

The project investigates banking deserts and cash infrastructure vulnerability across the Republic of Ireland by combining Census 2022 demographic datasets with spatial optimization models to identify critical versus redundant financial service locations, with a specific focus on vulnerable populations like the elderly and those with limited internet access.

---

## Key Methodologies & Tech Stack
* **Spatial Optimization**: Maximum Covering Location Problem (MCLP) modeling using Python (`spopt`, `geopandas`).
* **Routing & Accessibility**: Open Source Routing Machine (OSRM) for network-based travel time and distance matrices.
* **Demographic Vulnerability Index**: Census 2022 small-area statistics integration assessing digital exclusion and age dependency.
* **Data Visualization & Dashboarding**: Interactive Power BI dashboard communicating spatial gaps and policy recommendations.

---

## Repository Structure
```text
banking-deserts-ireland/
│
├── notebooks/                # Jupyter notebooks containing python code, data processing and MCLP models
├── outputs/                  # Exported maps, figures, and model evaluations
├── processed-data/           # Cleaned spatial layers and summary statistics
├── raw-data/                 # Directory for raw input datasets
└── NCG616_Dissertation_Banking_Deserts_Ireland.html   # Main analysis exported HTML report
```
---

## Raw Datasets & Reproduction Guide
* Due to file size limits, the large raw input files (such as the OSM .pbf extract and Census boundaries ZIP) are hosted separately.
* **Download Raw Data**: Head over to the Releases section on the right sidebar and download the files (.pbf and .zip).
* **Place Files**: Move the downloaded raw files into your local raw-data/ folder.
* **Update Paths**: Open the Jupyter notebooks and make sure to update the source and target file paths to match your local directory structure before running the scripts.

