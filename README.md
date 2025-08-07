# 🧱 Concrete Compressive Strength Prediction (PRCP-1019)
This repository contains the complete end-to-end data analysis and machine learning solution for predicting concrete compressive strength using its mix composition and age.

## 📌 Problem Statement
Concrete compressive strength is a critical measure in civil engineering. The strength depends on various constituents of the concrete mix such as cement, water, fly ash, slag, etc., along with the age of the concrete.

Goal:

Analyze and understand the patterns within the dataset using Exploratory Data Analysis (EDA).

Build a regression model that can accurately predict the compressive strength (MPa) of concrete based on its ingredients and age.

## 📂 Dataset Description
📄 Instances: 1030

🔢 Features: 8 quantitative input features, 1 output target variable

🌐 Source: Download Dataset (ZIP)

🧪 Features
| Feature                  | Unit         | Description                     |
| ------------------------ | ------------ | ------------------------------- |
| Cement                   | kg/m³        | Cement component                |
| Blast Furnace Slag       | kg/m³        | Byproduct from steel production |
| Fly Ash                  | kg/m³        | Industrial byproduct            |
| Water                    | kg/m³        | Mixing water                    |
| Superplasticizer         | kg/m³        | Chemical additive               |
| Coarse Aggregate         | kg/m³        | Gravel or crushed stone         |
| Fine Aggregate           | kg/m³        | Sand or crushed sand            |
| Age                      | Days (1–365) | Age of the concrete             |
| **Compressive Strength** | MPa          | **Target variable**             |

## Tasks Completed
### Exploratory Data Analysis (EDA)
* Missing value analysis
* Feature distributions and skewness correction
* Correlation heatmaps
* Scatter and box plots to identify patterns

### Machine Learning Model Development
* Data preprocessing and scaling
* Model training and testing using:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Performance comparison using R² Score, MAE, MSE, RMSE

## Model Comparison Report
| Model                   | R² Score | RMSE    |
| ----------------------- | -------- | ------- |
| Linear Regression       | 0.61     | 10.8    |
| Ridge Regression        | 0.62     | 10.6    |
| Random Forest Regressor | **0.91** | **5.2** |
| XGBoost Regressor       | 0.88     | 6.1     |

### ✅ Random Forest Regressor was selected as the final model due to its superior accuracy and robustness on unseen data

## Key Learnings
* Hands-on experience with a real-world regression task
* Understanding the importance of preprocessing in tabular datasets
* How to select and evaluate ML models for production-ready solutions

