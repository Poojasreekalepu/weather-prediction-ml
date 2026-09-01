# weather-prediction-ml
Weather prediction using machine learning algorithms as part of an L&TEduTech project, implementing KNN, SVM, Gradient Boosting, and XGBoost.
# Weather Prediction Using Machine Learning

This project was developed as part of the **L&T EduTech** program.

The project uses machine learning algorithms to predict weather conditions using the **Seattle Weather Dataset**.

## Objective

- Analyze the Seattle Weather Dataset
- Preprocess the data
- Apply different machine learning algorithms
- Compare their performance
- Identify the best-performing model

## Dataset

The Seattle Weather Dataset contains 1461 records with the following features:

- Date
- Precipitation
- Maximum Temperature
- Minimum Temperature
- Wind
- Weather

The target variable is **Weather**.

## Machine Learning Algorithms

The following algorithms were used:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost

## Data Preprocessing

- Removed the Date column
- Applied Label Encoding to weather labels
- Applied feature scaling
- Split the data into training and testing sets

## Results

| Algorithm | Accuracy |
|-----------|----------|
| KNN | 69.62% |
| SVM | 78.50% |
| Gradient Boosting | 83.28% |
| XGBoost | 81.91% |

**Gradient Boosting achieved the highest accuracy of 83.28%.**

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Project Files

- `weather_prediction.ipynb` - Jupyter Notebook containing the complete implementation
- `seattle-weather.xls` - Dataset used for the project
- `WEATHER PREDICTION USING MACHINE LEARNING ALGORITHMS.pdf` - Project report

## Future Scope

- Use larger weather datasets
- Include additional features such as humidity and pressure
- Apply deep learning models
- Develop a real-time weather prediction system

## Author

**Pooja Sree**

B.Tech CSE - Artificial Intelligence and Machine Learning
