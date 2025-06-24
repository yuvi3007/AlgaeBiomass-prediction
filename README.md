# 🌱 Algae Biomass Prediction Using ML

This project leverages **Linear Regression** and **Random Forest Regressor** models to predict **biomass production** from microalgae based on environmental and nutrient parameters. The goal is to model and optimize algal growth for applications in biofuel, wastewater treatment, and sustainability.

---

## 📌 Problem Statement

Microalgae are a promising source for biofuel and CO₂ capture. However, accurately predicting biomass production based on varying growth conditions (like light, nutrients, and time) is crucial for scaling their use.  
This project aims to build a regression pipeline that can **predict biomass concentration** using real or experimental datasets.

---

## 🔍 Project Overview

- **Data Preprocessing**: handled missing values, normalization, feature engineering
- **Modeling**: trained and compared Linear Regression and Random Forest Regressor
- **Evaluation**: used R², MAE, RMSE metrics to evaluate both models
- **Visualization**: plotted prediction vs actual biomass, feature importance, and error distribution

---

## 🧠 ML Models Used

| Model             | Description                                |
|------------------|--------------------------------------------|
| Linear Regression | Simple baseline model                      |
| Random Forest Regressor | Captures non-linear relationships; performed better overall |

---

## 📊 Results

| Metric   | Linear Regression | Random Forest |
|----------|-------------------|---------------|
| R² Score | 0.78              | 0.89          |
| MAE      | 1.34              | 0.72          |
| RMSE     | 2.01              | 1.12          |

🎯 **Random Forest Regressor outperformed Linear Regression** in all metrics.

---


