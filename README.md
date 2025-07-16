# Rural Credit & Carbon Intelligence Dataset
Alternate dataset for AI-based creditworthiness and soil carbon scoring in rural economies
## Overview
This dataset supports the development of responsible AI models that address financial inclusion and climate resilience in rural economies. It integrates alternative demographic and financial data with agro-environmental and remote sensing features to enable multi-task machine learning applications—particularly for **creditworthiness scoring** and **soil organic carbon (SOC) estimation**.

The dataset is designed for researchers, data scientists, and policymakers interested in the intersection of **AI for social good**, **climate-smart agriculture**, and **rural credit systems**.
---

## Dataset Structure

The dataset includes the following key components:

- **Demographic & Financial Variables**: Simulated thin-file rural borrower profiles including age, landholding size, psychometric scores, digital transaction frequency.
- **Agro-Environmental Variables**: Soil pH, SOC percentage, rainfall, and land surface temperature.
- **Remote Sensing Features**: NDVI, EVI, and land cover types extracted from publicly available satellite imagery.
- **Geospatial Metadata**: Coordinates, administrative codes, and satellite IDs.
- **Multi-task Labels**: 
  - `credit_score_label`: Credit risk classification (Low/Medium/High)
  - `soc_class_label`: SOC class (Low/Medium/High)
---

## Files Included

- `synthetic_dataset.csv` – Main data file with 30+ variables
- `Unified_Rural_Credit_Carbon_DataDictionary.csv` – Full data dictionary
- `Rural_Credit_Carbon_Workflow.png` – Process workflow diagram
- `README.txt` – This file
- `model_code/` – Folder containing sample ML scripts (optional)
- `ethical_use_and_model_card.pdf` – Ethical use policy and limitations (forthcoming)
---

## Use Cases

- Credit risk assessment for underserved rural borrowers
- SOC prediction for regenerative agriculture projects
- Multi-task learning demonstrations in AI fairness research
- Responsible AI benchmarking for ESG-aligned models

---

## Citation

If you use this dataset, please cite:
