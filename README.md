# project-03

# Pizza Delivery Analytics & Delay Prediction

## Project Overview

This project analyzes pizza delivery operations using customer order, traffic, restaurant, and delivery performance data.

The analysis focuses on:

* Customer ordering behavior
* Operational performance
* Traffic and peak-hour impact
* Seasonal delivery trends
* Delivery delay analysis
* Machine learning prediction models

The project also compares multiple regression models to predict delivery duration and identify the most important operational factors affecting delivery performance.

---

## Dataset

The dataset contains approximately 1,000 pizza delivery orders with features related to:

* Pizza type and size
* Toppings and order complexity
* Restaurant information
* Traffic conditions
* Peak-hour indicators
* Delivery duration and delay metrics
* Payment methods
* Time-based operational features

---

## Techniques Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Quarto

---

## Project Sections

1. Customer Segmentation & Preferences
2. Pricing & Value Perception
3. Operational Performance Analysis
4. Seasonal & Time-Based Trends
5. Delivery Duration Prediction

---

## Machine Learning Models

The following regression models were tested:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### Best Model Performance

| Model   | RMSE | R²     |
| ------- | ---- | ------ |
| XGBoost | 1.20 | 0.9788 |

---

## Key Findings

* Traffic conditions strongly increased delivery delays.
* Peak-hour demand significantly reduced operational efficiency.
* Delivery distance was the most important predictor of delivery duration.
* Larger and more complex pizza orders increased delivery time.
* XGBoost achieved the strongest predictive performance.

---

## Business Value

This project demonstrates how operational analytics and predictive modeling can support:

* Delivery optimization
* Resource allocation
* Demand management
* Operational planning
* Customer service improvement

---

## Repository Structure

```text
project-03/
│
├── pizza_analysis.qmd
├── README.md
├── Enhanced_pizza_sell_data_2024-25.xlsx
│
├── images/
│
└── outputs/
```

