# Explainable AI for Gold Price Prediction using SHAP

This project demonstrates how to apply SHAP (SHapley Additive exPlanations) to explain predictions made by machine learning models on gold price data. It focuses on interpreting feature contributions in Random Forest and Decision Tree models.

## Overview

The notebook explores the following steps:
- Applying SHAP to visualize and interpret model predictions
- Generating summary plots and force plots for model outputs
- Analyzing individual predictions to understand feature impacts
- Comparing feature effects across different models (Random Forest vs Decision Tree)

## Features

- Uses SHAP for detailed feature importance and contribution analysis
- Demonstrates explainability on gold price predictions
- Includes visualizations and breakdowns for specific samples
- Supports both Random Forest and Decision Tree models

## How to Run

This notebook is designed for **Google Colab**:

1. Upload and open the `.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Install dependencies if prompted (e.g., `shap`, `matplotlib`)
3. Run all cells in order to generate SHAP plots and insights

## Output

- SHAP summary plots for feature importance
- Detailed per-sample explanations showing how each feature affects predictions
- Comparison of explanations across different models
