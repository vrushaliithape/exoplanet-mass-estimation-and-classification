# exoplanet-mass-estimation-and-classification
Machine learning-based exoplanet mass estimation and classification using NASA Exoplanet Archive data.


An end-to-end data science project that uses machine learning techniques to estimate and classify exoplanet mass based on astronomical data from the NASA Exoplanet Archive. The project analyzes planetary and stellar features to predict exoplanet mass and categorize planets into high-mass and low-mass classes.

---

## 🌌 Project Overview
This project focuses on understanding the relationship between planetary characteristics and exoplanet mass. Using supervised machine learning models, the system performs:

- **Regression** to estimate exoplanet mass
- **Classification** to categorize exoplanets based on mass thresholds

The complete workflow — from data preprocessing to model evaluation — is implemented in a single Jupyter Notebook.

---

## 📊 Dataset
- **Source:** NASA Exoplanet Archive
- **Target Variable:**  
  - `pl_bmasse` — Planetary mass (Earth masses)
- **Features Used:**
  - `pl_radj` — Planet radius (Jupiter radius)
  - `pl_rade` — Planet radius (Earth radius)
  - `pl_orbeccen` — Orbital eccentricity
  - `st_rad` — Host star radius

---

## 🎯 Objective
- To predict exoplanet mass using regression models
- To classify exoplanets into high-mass and low-mass categories
- To evaluate and compare machine learning model performance

---

## 🧠 Key Features & Technical Details
- **Data Preprocessing:**  
  Cleaning, handling missing values, log transformation, and feature scaling
- **Machine Learning Models:**  
 classification
  - Logistic Regression  
  - Support Vector Classifier (SVC)  
  - naive bayes (gaussianNB,bernoullisNB)
  Regression-
  - Linear Regression  
  - DecisionTreeregressor
  - Random Forest Regression
- **Evaluation Metrics:**  
  
  - AUC-ROC score for classification  
  - R² score for regression

**visualization**-
*linear and decision tree regressor*-
-bar chart - r2_score
-bar chart - rmse
*decision tree regressor* -
- histogram -error distribution 
- scatterplot-actual vs predicted 
*linear regression*-
-scatter plot - best fit line 

*classification* -
heatmap-confusion matrix 

-

## 📈 Results
**regression performance **
- linear regression - r2 _score-**0.96**
- **Classification Performance:**
  accuracy -logistic -**0.99**