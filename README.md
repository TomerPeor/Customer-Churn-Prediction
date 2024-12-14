# Customer Churn Prediction

This repository contains a machine learning project focused on predicting customer churn for Accessibe, utilizing Python-based tools and libraries. The project demonstrates end-to-end handling of a churn dataset, including preprocessing, feature engineering, and model evaluation.

---

## Project Overview

Customer churn prediction is a critical task in understanding customer behavior and reducing attrition. This project builds and evaluates machine learning models to identify customers likely to stop using a service. The primary goal is to provide actionable insights to improve retention strategies.

---

## Features

### 1. **Data Preprocessing**
- Removal of leakage-inducing features such as `Churn Date` and other unique identifiers.
- Handling missing data and outliers effectively.

### 2. **Feature Engineering**
- Dropped irrelevant columns (e.g., `Account Name`, `Opportunity Name`) to improve model performance.
- Explored correlations and eliminated highly correlated features to avoid multicollinearity.

### 3. **Machine Learning Models**
- Experimented with multiple algorithms including Random Forest, XGBoost, and Logistic Regression.
- Fine-tuned hyperparameters using techniques like GridSearchCV.

### 4. **Evaluation Metrics**
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

---

## Future Work

- Enhance feature engineering by incorporating external data sources.
- Deploy the best model as an API for real-time predictions.
- Create dashboards for visualizing churn insights.

---

## Contact

For questions or feedback, please feel free to reach out:
- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

Thank you for visiting this repository. If you find it useful, please give it a ⭐!
