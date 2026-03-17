# Customer Booking Prediction

## Overview
This project builds a machine learning model to predict whether a customer will complete a flight booking using behavioral and trip-related features.

The goal is to identify high-intent customers early and support targeted marketing strategies.

---

## Problem Statement
Airlines need to understand which customers are likely to complete bookings in order to optimize marketing efforts and improve conversion rates.

This project models booking completion as a classification problem using historical customer data.

---

## Approach

- Performed data cleaning and preprocessing
- Handled categorical variables using one-hot encoding
- Addressed class imbalance using class-weighted Logistic Regression
- Scaled numerical features for model stability
- Evaluated models using recall, precision, and cross-validation

---

## Model Performance

- **Model Used:** Logistic Regression  
- **Recall (Booking Completion):** ~75%  
- **Precision:** ~30%  
- **Cross-validation Recall:** ~74–76%

The model prioritizes recall to minimize missed booking opportunities.

---

## Key Insights

- Route and destination significantly impact booking likelihood  
- Customers selecting add-ons (e.g., baggage) show higher purchase intent  
- Booking origin influences conversion behavior  

---

## Business Impact

- Enables early identification of high-intent customers  
- Supports targeted marketing campaigns  
- Helps improve conversion rates and revenue optimization  

---

## Visualization

![Feature Importance](images/feature_importance.png)

---

## Future Improvements

- Improve precision through model tuning (e.g., threshold optimization)  
- Test additional models (e.g., XGBoost)  
- Incorporate more customer behavioral features  

---

## Tech Stack

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---