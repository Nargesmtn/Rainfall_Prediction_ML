# Rainfall Prediction using Machine Learning

This project uses weather data from Australia to predict whether it will rain tomorrow.  
It includes full data preprocessing, modeling, evaluation, and model comparison.

---

## Dataset
Source: [IBM Cloud CSV Link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/_0eYOqji3unP1tDNKWZMjg/weatherAUS-2.csv)

Filtered locations: Melbourne, MelbourneAirport, Watsonia

---

## ML Pipeline Steps

- Data cleaning (null handling, filtering)
- Feature engineering (e.g., seasons)
- One-hot encoding of categorical variables
- Scaling numerical features
- Train-test split

---

## Models Trained

- **Random Forest Classifier** (tuned with GridSearchCV)
- **Logistic Regression**

Both models were evaluated using:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

---

## 🔍 Results Summary

| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Random Forest      | 0.84     | 0.75      | 0.51   | 0.61     |
| Logistic Regression| 0.83     | 0.69      | 0.51   | 0.59     |

> Random Forest performed slightly better but Logistic Regression offered greater interpretability.

---

## Visuals

- Top 20 Feature Importances
<img width="1038" alt="Screenshot 2025-07-01 at 1 57 07 PM" src="https://github.com/user-attachments/assets/47450de1-630a-480a-ab47-da18c8baa856" />
- Confusion Matrices for both models
<img width="550" alt="Screenshot 2025-07-01 at 1 58 42 PM" src="https://github.com/user-attachments/assets/8e496760-1d47-4153-bae8-530762c5b283" />
<img width="630" alt="Screenshot 2025-07-01 at 1 58 58 PM" src="https://github.com/user-attachments/assets/2b687921-3f95-4f1c-8f70-44e9dc18603e" />

---


## 🧠 Skills Demonstrated

- Data preprocessing
- Building pipelines with `scikit-learn`
- Model tuning with GridSearchCV
- Binary classification evaluation
