# weather-prediction-ml
Weather prediction using machine learning algorithms as part of an L&TEduTech project, implementing KNN, SVM, Gradient Boosting, and XGBoost.
# 🌦️ Weather Prediction Using Machine Learning

A machine learning project for predicting weather conditions using the
Seattle Weather Dataset. This project was developed as part of the
**L&T EduTech** program and focuses on implementing and comparing
multiple classification algorithms.

---

## 📌 Project Overview

Weather prediction plays an important role in areas such as agriculture,
transportation, and daily activities. Machine learning can be used to
analyze historical weather data and identify patterns that help predict
weather conditions.

In this project, four machine learning algorithms were implemented and
compared:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost

The models were evaluated using classification metrics and their
prediction accuracy was compared to identify the best-performing model.

---

## 🎯 Objectives

- Analyze the Seattle Weather Dataset
- Preprocess and clean the weather data
- Implement multiple machine learning classification algorithms
- Compare the performance of different models
- Identify the best-performing model for weather prediction

---

## 📊 Dataset

**Dataset:** Seattle Weather Dataset

The dataset contains **1,461 records** and the following attributes:

| Feature | Description |
|---|---|
| Date | Date of the observation |
| Precipitation | Amount of precipitation |
| Maximum Temperature | Maximum recorded temperature |
| Minimum Temperature | Minimum recorded temperature |
| Wind | Wind measurement |
| Weather | Weather condition |

### Target Variable

`Weather`

The target represents the weather condition to be predicted.

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

1. Removed the `Date` column.
2. Converted weather labels into numerical values using Label Encoding.
3. Applied feature scaling.
4. Split the dataset into training and testing datasets.

---

## 🤖 Machine Learning Models

### 1. K-Nearest Neighbors (KNN)

KNN classifies a data point based on the classes of its nearest
neighboring data points.

### 2. Support Vector Machine (SVM)

SVM finds an optimal decision boundary for separating different classes.

### 3. Gradient Boosting

Gradient Boosting combines multiple weak learners sequentially to
build a stronger predictive model.

### 4. XGBoost

XGBoost is an optimized gradient boosting algorithm designed for
efficient and accurate machine learning.

---

## 📈 Results

The models were evaluated based on their prediction accuracy.

| Algorithm | Accuracy |
|---|---:|
| KNN | 69.62% |
| SVM | 78.50% |
| Gradient Boosting | **83.28%** |
| XGBoost | 81.91% |

### 🏆 Best Performing Model

**Gradient Boosting** achieved the highest reported accuracy of
**83.28%** among the four models.

The model performed particularly well for the **rain** and **sunny**
weather classes. The lower performance for **drizzle** and **snow**
was attributed to the smaller number of samples in those classes.

---

## 📋 Evaluation Metrics

The project evaluates model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The confusion matrix is used to visualize the classification
performance of the models.

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **XGBoost**
- **Matplotlib**
- **Seaborn**

---

## 📁 Project Structure

```text
weather-prediction-ml/
│
├── data/
│   └── seattle-weather.xls
│
├── notebooks/
│   └── weather_prediction.ipynb
│
├── report/
│   └── WEATHER PREDICTION USING MACHINE LEARNING ALGORITHMS.pdf
│
└── README.md
