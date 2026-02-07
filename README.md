# Sports Analytics: Interpretable ML for Team & Player Performance Prediction

This project implements a **reproducible sports analytics pipeline** to predict **IPL team outcomes and player performance** using **simple, readily-available cricket statistics** (e.g., batting average/strike rate, wickets, economy). The aim is to bridge the gap between **black-box academic models** and **practical, interpretable decision support** for analysts, coaches, and fantasy-cricket users.

## Dissertation Summary
The dissertation builds supervised learning models using historical IPL data (2008–2024), including:
- **Team outcome prediction** using interpretable ML models (SVM, Decision Tree, Random Forest, XGBoost)
- **Player performance forecasting** (batting/bowling/fielding) using regression-style ranking/forecasting
- **Time-aware evaluation** with season-based splits: **train (2008–2021), validation (2022), test (2023)**

Key results:
- **XGBoost** achieved the best discrimination with **macro OvR AUC ≈ 0.646**
- **Random Forest** achieved the best **top-1 accuracy ≈ 39%** for multi-class winner prediction  
(These headline results are reported in the dissertation report.)  

## Data Source
Dataset: Kaggle **“IPL Complete Dataset (2008–2024)”** (Version 3; updated through 2024).  
Files used:
- `matches.csv` (match-level metadata)
- `deliveries.csv` (ball-by-ball records)

## Repository Structure (recommended)
