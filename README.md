# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a patient is likely to have heart disease using a **Random Forest Classifier**. It demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, feature importance analysis, and model serialization using Joblib.

The notebook is implemented in **Python** using **Google Colab** and follows industry-standard machine learning practices.

---

## 🎯 Project Objectives

- Explore and understand the dataset
- Preprocess categorical and numerical data
- Train a Random Forest classification model
- Evaluate model performance using multiple metrics
- Analyze feature importance
- Save the trained model for future predictions

---

## 📂 Dataset

The dataset contains medical information about patients and whether they have heart disease.

### Features

| Feature | Description |

| Age | Age of the patient |
| Sex | Gender (Male/Female) |
| ChestPainType | Type of chest pain |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol level |
| FastingBS | Fasting blood sugar |
| RestingECG | Resting electrocardiogram results |
| MaxHR | Maximum heart rate achieved |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression induced by exercise |
| ST_Slope | Slope of the peak exercise ST segment |

**Target Variable**

- **HeartDisease**
  - 1 = Heart Disease
  - 0 = No Heart Disease

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Google Colab

---

## ⚙️ Machine Learning Workflow

```
Load Dataset
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Label Encoding
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Random Forest Classifier
      ↓
Model Evaluation
      ↓
Feature Importance
      ↓
Save Trained Model
```

---

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📈 Feature Importance

The project analyzes the contribution of each feature to the model's predictions using the built-in feature importance of the Random Forest algorithm.

---

## 💾 Saved Model Files

The following files are generated after training:

- `heart_model.pkl` – Trained Random Forest model
- `scaler.pkl` – StandardScaler object
- `label_encoders.pkl` – Label encoders for categorical features

These files allow future predictions without retraining the model.

---

Aspiring Data Analyst | Machine Learning Enthusiast

If you found this project useful, feel free to ⭐ the repository.
