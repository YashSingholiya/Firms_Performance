# Firm Performance 

This repository contains the implementation of a machine learning project aimed at predicting firm performance using financial indicators by leveraging various machine learning models .

---

## Table of Contents

- [Abstract](#abstract)
- [Features and Data](#features-and-data)
- [Models Implemented](#models-implemented)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## Abstract

This project investigates firm prediction using machine learning. By analyzing financial features such as income, liabilities, and expenses, we developed and evaluated several models. The **Bayesian Ridge Regressor** emerged as the top-performing model, achieving high accuracy and low prediction error. The project demonstrates the effectiveness of ensemble methods in firms prediction.

---

## Features and Data

### Dataset
The dataset comprises financial records from various firms with the following key features:
- **Total income**
- **Total liabilities**
- **Total assets**
- **Profit after tax**
- **Total expenses**
- **Indirect taxes**
- **Rent & lease rent**
- **Sales**
- **Income from financial services**
- **Other income**

### Preprocessing
1. **Handling Missing Values**: Missing values were imputed using the mean of the respective columns.
2. **Feature Scaling**: StandardScaler was used to normalize feature values.
3. **Exploratory Data Analysis (EDA)**: Visualizations like correlation heatmaps were used to understand relationships between features.

---

## Models Implemented

The following regression models were used and evaluated:
- **Random Forest Regressor** 
- **Decision Tree Regressor**
- **XGBoost Regressor**
- **Gradient Boosting Regressor**
- **AdaBoost Regressor**
- **Bayesian Ridge Regressor**  (Best Performer)

### Evaluation Metrics
- **Mean Squared Error (MSE)**
- **Mean Squared Logarithmic Error (MSLE)**
- **R-squared (R²)**

---

## Setup

### Prerequisites
- Python 3.8 or higher
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/firm-performance-ml.git
   cd firm-performance-ml
