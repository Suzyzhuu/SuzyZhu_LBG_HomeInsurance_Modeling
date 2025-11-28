
# Lloyds Banking Group – Home Insurance Modelling Task
Author: Suzy Zhu  
Date: November 2025

## Overview
This repository contains:
- The modelling notebook used to ingest raw campaign + mortgage datasets
- Data preparation and feature engineering pipeline
- Machine learning models (Logistic Regression, Random Forest, CatBoost)
- Evaluation metrics and visualisations
- SHAP explainability outputs and outreach lists

## How to Run
1. Open Google Colab at: https://colab.research.google.com/
2. Upload the file:
   - futurebank_home_insurance.ipynb
3. Upload the TWO raw CSVs provided by Lloyds:
   - Dummy dataset campaign.csv
   - dummy dataset mortgage.csv
4. Run all cells from top to bottom.
5. Outputs (CSVs and plots) will be automatically saved to `/assignment_outputs/`.

## Key Outputs
- Model comparison (AUROC, AUPRC)
- SHAP global summary
- Outreach lists (Top 1%, 5%, 10%)
- Feature importance
- ROC/PR/Lift curves

## Dependencies
All dependencies install automatically in the notebook:
- catboost
- shap
- scikit-learn
- pandas, numpy, matplotlib
