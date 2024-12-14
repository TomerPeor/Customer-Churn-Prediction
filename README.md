# Customer Churn Prediction

![image](https://github.com/user-attachments/assets/48d88648-1aa6-4f63-a334-76294f3ad960)

This repository contains a machine learning project focused on predicting customer churn for Accessibe, utilizing Python-based tools and libraries. The project demonstrates end-to-end handling of a churn dataset, including preprocessing, feature engineering, and model evaluation.

---

## Project Overview

Customer churn prediction is a critical task in understanding customer behavior and reducing attrition. This project builds and evaluates machine learning models to identify customers likely to stop using a service. The primary goal is to provide actionable insights to improve retention strategies.

---

## Features

### 1. **Data Preprocessing**
- Removal of leakage-inducing features such as `Churn Date` and other unique identifiers.
- Handling missing data and outliers effectively.

  ### 2. **Exploratory Data Analysis (EDA)**
- **Numerical Features**:
  - Features like `Average Monthly Traffic` and `Domain Page Count` exhibited skewed distributions, addressed using scaling techniques.
  - Outliers were identified and visualized using boxplots for features such as `Total ARR` and `FN ARR`.
- **Categorical Features**:
  - The top categories for `Website Category New` showed significant concentration in a few labels, as visualized through bar plots.
  - Certain features, like `Plan` and `CMS-Builder`, revealed patterns linked to churn behavior.
- **Correlation Heatmap**:
  - A strong correlation was observed between `FN ARR` and `Total ARR`, influencing feature selection decisions.

### 3. **Feature Engineering**
- Dropped irrelevant columns (e.g., `Account Name`, `Opportunity Name`) to improve model performance.
- Explored correlations and eliminated highly correlated features to avoid multicollinearity.

### 4. **Machine Learning Models**
- Experimented with multiple algorithms including Random Forest, XGBoost, and Logistic Regression.
- Fine-tuned hyperparameters using techniques like GridSearchCV.

### 5. **Evaluation Metrics**
- Used metrics such as Accuracy, Precision, Recall, and F1-score to measure model performance.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, scikit-learn, XGBoost
- **Tools**: Jupyter Notebook, Google Colab

---

## Results

- **Best Model**: Random Forest Classifier achieved the highest F1-score on the test set.
- **Key Insights**:
  - Subscription renewal behavior was a major predictor of churn.
  - Models benefited significantly from careful preprocessing and feature selection.
 
    <img width="344" alt="image" src="https://github.com/user-attachments/assets/4cbcf3e8-ca0a-484e-aa7d-9ba954986b2b" />


---

## Future Work

- Enhance feature engineering by incorporating external data sources.
- Deploy the best model as an API for real-time predictions.
- Create dashboards for visualizing churn insights.

---

Thank you for visiting this repository. If you find it useful, please give it a ⭐!
