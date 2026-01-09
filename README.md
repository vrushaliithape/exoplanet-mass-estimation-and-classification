# Exoplanet Mass Estimation and Classification

Machine learning–based exoplanet mass estimation and classification using data from the NASA Exoplanet Archive.

This is an end-to-end data science project that applies supervised machine learning techniques to estimate exoplanet mass and classify exoplanets into high-mass and low-mass categories based on astronomical features.

---

## 🌌 Project Overview

This project explores the relationship between planetary and stellar characteristics and exoplanet mass. Using regression and classification models, the system:

- Estimates exoplanet mass using regression techniques
- Classifies exoplanets into high-mass and low-mass categories
- Evaluates and compares multiple machine learning models

The complete workflow — from data preprocessing to model evaluation — is implemented in a single Jupyter Notebook.

---

## 📊 Dataset

**Source:** NASA Exoplanet Archive  
The dataset used in this project is publicly available and was obtained from the NASA Exoplanet Archive.

Dataset link: https://exoplanetarchive.ipac.caltech.edu/

### Target Variable
- **pl_bmasse** — Planetary mass (Earth masses)

### Features Used
- **pl_radj** — Planet radius (Jupiter radius)
- **pl_rade** — Planet radius (Earth radius)
- **pl_orbeccen** — Orbital eccentricity
- **st_rad** — Host star radius

---

## 🎯 Objectives

- Predict exoplanet mass using regression models
- Classify exoplanets into high-mass and low-mass categories
- Evaluate and compare machine learning model performance

---

## 🧠 Methodology & Technical Details

### Data Preprocessing
- Data cleaning and handling missing values
- Log transformation for skewed features
- Feature scaling for machine learning models

### Machine Learning Models

#### Classification Models
- Logistic Regression
- Support Vector Classifier (SVC)
- Naive Bayes (GaussianNB, BernoulliNB)

#### Regression Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Evaluation Metrics

### Classification
- Accuracy
- F1-score
- AUC–ROC
- Confusion Matrix

### Regression
- R² Score
- RMSE

---

## 📊 Visualizations

- Bar charts for R² score comparison
- Bar chart for RMSE (Decision Tree Regressor)
- Histogram of error distribution
- Scatter plot: Actual vs Predicted (Linear Regression)
- Best-fit line for regression
- Confusion matrix heatmap for classification
- Pie chart for F1-score comparison across classifiers

---

## 🚀 Results

### Regression Performance
- **Linear Regression:** R² score = **0.96**
- **Random Forest Regression:** Best overall performance

### Classification Performance
- **Logistic Regression:** Accuracy = **0.99**
- High F1-score consistency across classifiers

---
