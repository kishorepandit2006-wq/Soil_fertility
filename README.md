# 🌱 Soil Fertility Classification Using Machine Learning

## 📌 Project Overview

Soil Fertility Classification is a Machine Learning project designed to predict soil fertility based on its chemical properties, nutrient levels, soil type, crop type and geographical information.

The system classifies soil into three categories:

- 🔴 Low Fertility
- 🟡 Medium Fertility
- 🟢 High Fertility

The project aims to support precision agriculture and help farmers make informed decisions about soil management and crop cultivation.

## 🎯 Project Objectives

- Analyze soil properties and nutrient levels.
- Perform data cleaning and preprocessing.
- Perform Exploratory Data Analysis (EDA).
- Identify important features affecting soil fertility.
- Train and compare multiple Machine Learning algorithms.
- Improve model performance using hyperparameter tuning.
- Predict the fertility class of new soil samples.

## 📊 Dataset Information

**Dataset:** `soil_fertility_classification_1000.csv`

| Parameter | Details |
|---|---|
| Total samples | 1,000 |
| Total columns | 20 |
| Input features | 16 |
| Target variable | Fertility_Class |
| Number of classes | 3 |
| Missing values | 0 |
| Duplicate records | 0 |
| Training samples | 800 |
| Testing samples | 200 |

### Dataset Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Soil pH
- Organic Carbon
- Electrical Conductivity
- Sulphur
- Zinc
- Boron
- Iron
- Manganese
- Copper
- State and District
- Soil Type
- Crop Type

### Class Distribution

| Fertility Class | Samples | Percentage |
|---|---:|---:|
| Low Fertility | 319 | 31.9% |
| Medium Fertility | 596 | 59.6% |
| High Fertility | 85 | 8.5% |

## ⚙️ Project Pipeline

1. Dataset Collection
2. Data Understanding
3. Data Cleaning and Validation
4. Exploratory Data Analysis
5. Correlation Analysis
6. Train-Test Split
7. Data Preprocessing
8. Feature Selection
9. Machine Learning Model Training
10. Five-Fold Cross-Validation
11. Hyperparameter Tuning
12. Model Evaluation and Comparison
13. Feature Importance Analysis
14. Model Saving
15. Soil Fertility Prediction

## 🧹 Data Preprocessing

The following preprocessing techniques are implemented:

- Missing value detection
- Duplicate record detection
- Invalid soil measurement detection
- Median imputation for numerical features
- Most frequent imputation for categorical features
- StandardScaler for feature scaling
- OneHotEncoder for categorical data
- SelectKBest with ANOVA F-test for feature selection
- Stratified 80:20 train-test split

Fertility_Score and identification columns are excluded from the input features to reduce data leakage and avoid unnecessary information.

##
