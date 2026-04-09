# ⚽ Premier League Match Predictor

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Wrangling-150458.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

A machine learning classification project designed to predict the outcomes of English Premier League (EPL) matches using historical match data.

## 📖 Project Overview
Predicting football match outcomes involves cutting through highly noisy data to find underlying statistical signals. This project utilizes historical match statistics sourced from Kaggle to classify future match results (Home Win, Away Win, or Draw). 

Instead of relying on black-box algorithms, this project leverages **Logistic Regression** to establish a highly interpretable, statistically grounded baseline that provides clear probability outputs for each match outcome.

## 🧠 Modeling Approach
* **Algorithm:** Logistic Regression (Multiclass)
* **Data Source:** Kaggle Premier League Dataset
* **Key Challenges Addressed:** * Parsing and cleaning historical match data.
  * Feature engineering for team form, historical head-to-head records, and home-field advantage.
  * Translating statistical probabilities into actionable predictions.

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install pandas numpy scikit-learn
