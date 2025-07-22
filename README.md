# Heart-Disease-
Heart Disease Prediction using ML: Built a Random Forest model to assess heart disease risk from clinical data (age, cp, chol, trestbps, thalach, etc.). Included data cleaning, feature engineering, and evaluation (accuracy, AUC). Deployed a app for real-time risk prediction and interactive user input.

Smart Healthcare Diagnosis – Heart Disease Prediction (Random Forest)
This project uses machine learning (Random Forest Classifier) to predict the likelihood of heart disease in patients based on clinical parameters. It includes data preprocessing, model training, evaluation, and a Streamlit web app for real-time predictions.

Key Features
Heart Disease Prediction: Uses age, blood pressure, cholesterol, ECG results, etc., for prediction.

Random Forest Model: High accuracy and robust performance.

Visualization: Confusion matrix, ROC curve, and feature importance plots.

Streamlit App: Interactive web UI for predictions.

#Project Structure

Smart-Healthcare-RF/
│
├── data/
│   └── heart_disease_uci.csv
│
├── model_assets/
│   └── heart_rf_pipeline.joblib
│
├── heart_rf_training.py
├── utils.py
├── app.py
├── requirements.txt
└── README.md


#Dataset
We use the Cleveland Heart Disease dataset which includes:

13 features: age, sex, cp (chest pain), trestbps (BP), chol (cholesterol), fbs, restecg, thalach, exang, oldpeak, slope, ca, thal.

Target: 1 (Heart Disease) or 0 (No Disease).


#Future Improvements
Deploy on Heroku or AWS.

Add XGBoost or deep learning models.

Improve UI with advanced charts.

