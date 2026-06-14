# Heart Disease Prediction

## Project Overview
Heart Disease Prediction is a machine learning project developed to predict whether a patient is likely to have heart disease based on various medical attributes. The goal is to assist healthcare professionals in identifying high-risk patients at an early stage.

## Problem Statement
The objective of this project is to build a predictive model that can accurately classify patients as having heart disease or not based on their medical information.

## Dataset Information
The dataset contains patient health records with features such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression (Oldpeak)
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease Presence)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Exploratory Data Analysis (EDA)
The following analyses were performed:

- Distribution of numerical features
- Box plots for outlier detection
- Correlation heatmap
- Target variable distribution
- Feature-wise comparison with target variable
- Scatter plots and grouped box plots

## Data Preprocessing
- Missing value handling
- Data cleaning
- Feature selection
- Train-Test Split
- Feature Scaling

## Machine Learning Models
The following models were evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Hyperparameter Tuning
GridSearchCV was used to optimize model parameters and improve model performance.

## Model Evaluation Metrics
The models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

## Results
- Best Model: Logistic Regression
- Training Accuracy: 86.11%
- Tuned Model Accuracy: 83.33%

The model demonstrated good performance in predicting the presence of heart disease and can be used as a decision-support tool.

## Project Structure

Heart-Disease-Prediction/
│
├── data/
├── notebooks/
├── images/
├── reports/
├── README.md
└── requirements.txt

## Key Insights
- Chest pain type showed a strong relationship with heart disease.
- Maximum heart rate achieved was an important predictor.
- ST depression (Oldpeak) significantly influenced prediction results.
- Several clinical features were highly correlated with heart disease occurrence.

## Future Improvements
- Test advanced ensemble models
- Perform deeper feature engineering
- Deploy the model using Streamlit or Flask
- Use larger healthcare datasets for improved generalization

## Author

Likhitha  
Aspiring Data Analyst | Data Science Enthusiast
