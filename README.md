# Car Price Prediction: Australian Vehicles 🚗💰 

This repository contains the code and data analysis for predicting car prices using machine learning. The project focuses on an Australian vehicle dataset and includes data cleaning, exploratory data analysis (EDA), and building predictive models to estimate car prices based on various features.

---

## 📝 Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Key Features](#key-features)
4. [Technologies Used](#technologies-used)
5. [Project Workflow](#project-workflow)
6. [Results and Insights](#results-and-insights)
7. [Future Improvements](#future-improvements)

---

## 📖 Introduction
Car prices are influenced by various factors such as mileage, brand, fuel type, and engine size. This project analyzes and predicts car prices using a dataset of Australian vehicles. The goal is to explore the relationships between car features and their prices, clean the dataset, and build a machine learning model to predict prices accurately.

---

## 📊 Dataset Overview
- **Dataset:** Australian vehicle listings.
- **Size:** 16,734 records.
- **Target Feature:** `Price`
- **Key Features:**
  - `Kilometres`
  - `Year`
  - `Engine Size`
  - `Transmission`
  - `Fuel Consumption`
  - `Location`
  - `Brand`
- **Cleaning Steps:**
  - Removed invalid or missing values.
  - Parsed and standardized numerical and categorical data.
  - Handled outliers and imbalanced distributions.

---

## ✨ Key Features
- Comprehensive data cleaning and preprocessing pipeline.
- Exploratory data analysis (EDA) with visualizations.
- Scatterplots, histograms, and heatmaps for understanding feature relationships.
- Predictive modelling using machine learning techniques.
- Model evaluation with metrics like R-squared and RMSE.

---

## 💻 Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn
  - Jupyter Notebook

---

## 🛠 Project Workflow
1. **Data Cleaning:**
   - Removed invalid placeholders (e.g., '-', 'POA').
   - Extracted numerical data from `FuelConsumption` and `Location`.
   - Handled missing values and converted features to appropriate data types.
2. **EDA:**
   - Explored feature distributions and correlations.
   - Visualized data using scatterplots, count plots, and heatmaps.
3. **Predictive Modelling:**
   - Built machine learning models to predict car prices.
   - Split data into training and testing sets (80%-20%).
   - Evaluated model performance with R-squared and RMSE metrics.

---

## 📈 Results and Insights

### Key Findings:
- Price decreases as kilometres driven increase.
- Newer cars and those with larger engines tend to have higher prices.
- Certain brands hold higher market value.

### Model Performance:
- Achieved satisfactory predictions with R-squared and RMSE metrics.

---

## 🚀 Future Improvements

- Experiment with advanced ML models (e.g., XGBoost, Random Forests).
- Incorporate feature engineering for categorical variables (e.g., one-hot encoding).
- Use hyperparameter tuning to optimize model performance.
- Add more data sources for better generalization.

