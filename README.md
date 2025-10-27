# Project Samarth – Intelligent Q&A System Prototype

## Overview

Project Samarth is a modular and interactive Q&A engine designed to extract insights from Indian government datasets using natural-language queries. This prototype demonstrates analysis and visualization for real, public datasets sourced from [data.gov.in](https://data.gov.in).

---

## Features

- **Data-driven Q&A:** Get answers to domain-specific queries about rainfall (Tamil Nadu) and crop production (Karnataka).
- **Multiple Query Types:** Analyze top/wettest/driest districts, averages, yields, above-average performers, and per-district stats.
- **Readable Outputs:** Responses are shown as formatted tables, lists, or concise text.
- **Visualizations:** Includes bar plots and summary statistics.
- **Real-world Data Handling:** Transparently handles cases when district lists do not match between datasets.
- **Easy to Extend:** Ready to expand to more states, years, or domains.

---

## Datasets Used

- **Rainfall Data:** District-wise rainfall statistics for Tamil Nadu  
  _Source: data.gov.in, India Meteorological Department_

- **Crop Production Data:** District-wise crop yield and production for Karnataka  
  _Source: data.gov.in, Ministry of Agriculture_

---

## Usage

1. Clone/download the repository.
2. Open `Project_Samarth.ipynb` (the main Jupyter notebook).
3. Ensure the datasets (`rainfall_districts.csv`, `crop_production.csv`) are present locally.
4. Run the notebook step by step:
    - **Setup & Imports**
    - **Load Data**
    - **Clean Data**
    - **Q&A Demos:** Try queries like `"wettest districts"`, `"average rainfall"`, `"top 3 districts by production"`, `"yield in Bagalkote"`, etc.
    - **Visualizations**

_Note: Rainfall and crop data here cover different states; the notebook analyzes each independently and shows this limitation openly._

---

## Examples

### Rainfall Q&A (Tamil Nadu):

- **Wettest districts:** Top 3 by rainfall
- **Average rainfall:** State average across districts
- **Above-average rainfall:** Districts > mean rainfall

### Crop Q&A (Karnataka):

- **Top 3 by production:** Leaders by all-season output
- **Average yield:** State average
- **District yield lookup:** Yield in a selected district

---

## Structure

- `Project_Samarth.ipynb`: Main notebook
- `rainfall_districts.csv`: Rainfall data for Tamil Nadu
- `crop_production.csv`: Crop data for Karnataka

---

## Limitations

- Unable to do rainfall-crop correlation at the district level due to district mismatch
- Ready to extend once overlapping data is sourced

---

## Acknowledgements

- [data.gov.in](https://data.gov.in)
- India Meteorological Department
- Ministry of Agriculture & Farmers Welfare, Government of India

---

v
