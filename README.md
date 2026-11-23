# Heart Attack Risk Classification Using Machine Learning

## 1. Project Overview

This project focuses on predicting heart disease risk using Machine Learning classification algorithms.

The model analyzes patient health indicators and medical attributes to classify individuals based on their likelihood of having heart disease.

The objective is to develop and evaluate multiple classification models to identify an effective approach for heart disease risk prediction.

## 2. Problem Statement

Heart disease is one of the major health concerns worldwide. Early identification of potential risk factors can support timely medical assessment and intervention.

This project applies Machine Learning classification techniques to analyze patient health information and predict heart disease risk based on historical medical data.

## 3. Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Understand relationships between patient health indicators and heart disease.
- Clean and preprocess the dataset.
- Handle missing values and categorical variables.
- Perform feature encoding and scaling where required.
- Handle class imbalance using SMOTE, if applicable.
- Train multiple Machine Learning classification models.
- Perform hyperparameter tuning.
- Evaluate and compare model performance.
- Select the best-performing classification model.

## 4. Dataset Description

The project uses a heart disease dataset containing patient health indicators and medical information.

**Common dataset features may include:**

- Age: Patient's age.
- Gender: Patient's gender.
- Chest Pain Type: Type of chest pain.
- Resting Blood Pressure: Blood pressure at rest.
- Cholesterol: Serum cholesterol level.
- Fasting Blood Sugar: Fasting blood sugar indicator.
- Resting ECG: Resting electrocardiographic results.
- Maximum Heart Rate: Maximum heart rate achieved.
- Exercise-Induced Angina: Angina caused by exercise.
- ST Depression: ST segment depression.
- Target: Heart disease classification label.

*Note: Update these features according to the actual columns in your dataset.*

## 5. Technologies and Libraries Used

- **Programming Language:** Python
- **Data Manipulation:** NumPy, Pandas
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Class Imbalance Handling:** Imbalanced-learn (SMOTE)
- **Model Saving:** Joblib, Pickle
- **Deployment:** Streamlit

## 6. Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier
4. Support Vector Classifier (SVC)
5. Gradient Boosting Classifier
6. XGBoost Classifier

## 7. Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Handling Missing Values
6. Categorical Feature Encoding
7. Feature Scaling
8. Train-Test Split
9. Handling Class Imbalance using SMOTE&#x20;
10. Model Training
11. Hyperparameter Tuning
12. Model Evaluation
13. Model Comparison
14. Best Model Selection
15. Heart Disease Risk Prediction

## 8. Model Evaluation Metrics

The classification models are evaluated using:

- **Accuracy:** Measures the proportion of correctly classified predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-Score:** Calculates the harmonic mean of precision and recall.
- **Confusion Matrix:** Provides a detailed view of correct and incorrect predictions.

These metrics help compare classification performance and identify a suitable model.

## 9. Best Model Selection

Support Vector Classifier (SVC) achieved an F1-score of approximately **0.875** in the previous model evaluation.

The final model selection should consider precision, recall, F1-score and the importance of false negatives, rather than accuracy alone.

## 10. Deployment

The selected Machine Learning model can be integrated into a Streamlit application.

The application allows users to enter relevant patient health information and receive a model-generated heart disease risk classification.

**Note:** This project is for educational purposes and is not a substitute for professional medical diagnosis or advice.

## 11. Real-World Applications

- Heart disease risk assessment.
- Analysis of patient health indicators.
- Early identification of potential risk patterns.
- Supporting healthcare data analysis.
- Medical research and predictive analytics.

## 12. Project Structure

```text
Heart-Attack-Risk-Classification/
│
├── README.md
├── requirements.txt
├── Heart_Attack_Risk_Classification_Aarya.ipynb
│
├── models/
│   └── heart_model.pkl
│
└── images/
    ├── correlation_matrix.png
    ├── confusion_matrix.png
    └── model_comparison.png
```

*Note: Your current repository contains the README, requirements file and notebook. Add the models and images folders only if you upload those files.*

## 13. Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/naik-aarya/Heart-Attack-Risk-Classification.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Heart-Attack-Risk-Classification
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

Open the `Heart_Attack_Risk_Classification_Aarya.ipynb` notebook in Google Colab or Jupyter Notebook and execute the cells.

## 14. Conclusion

This project demonstrates the application of Machine Learning classification algorithms for heart disease risk prediction.

By implementing and comparing multiple classification models, the project explores how patient health indicators can be used to identify patterns associated with heart disease.

It provides practical experience in data preprocessing, exploratory data analysis, feature engineering, handling class imbalance, classification modelling, hyperparameter tuning and model evaluation.

---

**Author:** Aarya Naik

**GitHub:** [https://github.com/naik-aarya](https://github.com/naik-aarya)

**Repository:** [https://github.com/naik-aarya/Heart-Attack-Risk-Classification](https://github.com/naik-aarya/Heart-Attack-Risk-Classification)

