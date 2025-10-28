Heart Disease Prediction using Machine Learning
📘 Overview

This project aims to predict the likelihood of heart disease in a patient based on various medical attributes such as age, sex, chestpain, blood pressure, cholesterol level, and more. The dataset used is derived from publicly available heart disease datasets (e.g., UCI Machine Learning Repository).
By leveraging machine learning models, the goal is to assist in early detection and prevention of heart disease.

🧠 Objectives

Analyze the relationship between medical parameters and heart disease.

Build and evaluate predictive models for classification.

Identify the most important features influencing heart disease risk.

Provide a reproducible and interpretable analysis pipeline.

📊 Dataset

The dataset typically includes the following columns:

Feature	Description
age	Age of the individual
sex	Gender (1 = male, 0 = female)
cp	Chest pain type (0–3)
restbps	Resting blood pressure
chol	Serum cholesterol (mg/dl)
fbs	Fasting blood sugar > 120 mg/dl
restecg	Resting ECG results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression induced by exercise
slope	Slope of the peak exercise ST segment
ca	Number of major vessels (0–3) colored by fluoroscopy
thal	Thalassemia type
AHD (target	1) = Heart disease, 0 = No heart disease

⚙️ Technologies Used

Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for visualization

Scikit-learn for machine learning models (e.g., Logistic Regression)

Jupyter Notebook

🔍 Model Building

Data Preprocessing: Handling missing values, normalization, encoding categorical features.

Model Training: Using multiple ML algorithms for comparison.

Evaluation: Accuracy, Precision

Feature Importance: Identifying top predictors of heart disease.

📈 Results

Achieved ~81% accuracy depending on the model and parameter tuning.

Logistic Regression performed best overall.

Future Improvements

Implement deep learning models for improved accuracy.

Add explainable AI (SHAP/LIME) for interpretability.

Deploy using Streamlit or Flask for web use.

👨‍💻 Author

Chukwuma Samuel
