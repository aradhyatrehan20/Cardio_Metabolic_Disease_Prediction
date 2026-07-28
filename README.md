# 🩺 Cardio-Metabolic Risk Prediction using Machine Learning

An end-to-end Machine Learning application that predicts the likelihood of **Heart Disease** and **Diabetes** using patient health parameters through an interactive **Streamlit** web interface.

This project was developed as part of my undergraduate coursework to understand the complete machine learning workflow—from data preprocessing and model training to deployment of predictive models.

---

## 🎯 Problem Statement

Heart disease and diabetes are among the most common chronic diseases worldwide. Early identification of individuals at risk can support timely medical intervention and informed healthcare decisions.

This project demonstrates how supervised machine learning algorithms can be used to predict the likelihood of these diseases based on clinical health indicators.

---

## 🚀 Features

- Heart Disease Prediction
- Diabetes Prediction
- Interactive Streamlit Web Application
- User-friendly Input Forms
- Instant Prediction Results
- Separate Machine Learning Models for Each Disease

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- Jupyter Notebook

---

## 🤖 Machine Learning Models

This project uses two supervised machine learning classification algorithms.

| Prediction Task | Model |
|-----------------|-------|
| Heart Disease Prediction | Logistic Regression |
| Diabetes Prediction | Support Vector Machine (SVM - Linear Kernel) |

Both models were trained using Scikit-learn and evaluated before deployment in the Streamlit application.

---

## 📂 Dataset

The project uses publicly available healthcare datasets containing patient health information.

### Heart Disease Dataset

Features include:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia

### Diabetes Dataset

Features include:

- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

---

## 📈 Project Workflow

```
Medical Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Model Serialization (Pickle)
        │
        ▼
Streamlit Web Application
        │
        ▼
Disease Prediction
```



## 📸 Application Screenshots

### Diabetes Prediction

<img src="Diabetes Prediction.jpeg" width="900">

### Heart Disease Prediction

<img src="Heart Disease Prediction.jpeg" width="900">

---

## ✨ Project Highlights

- Built separate machine learning models for predicting heart disease and diabetes.
- Trained and evaluated classification models using Scikit-learn.
- Developed an interactive Streamlit application for real-time predictions.
- Implemented an end-to-end machine learning workflow from preprocessing to deployment.
- Gained practical experience in deploying ML models as web applications.

---

## 📖 Key Learnings

Through this project, I gained hands-on experience with:

- Data preprocessing
- Supervised Machine Learning
- Classification Algorithms
- Model Evaluation
- Streamlit Deployment
- Building Interactive ML Applications

---

## 💡 Future Improvements

- Hyperparameter tuning to improve model performance
- Compare additional classification algorithms
- Add probability/confidence scores for predictions
- Improve UI and input validation
- Deploy the application on Streamlit Cloud
- Integrate Explainable AI techniques (SHAP/LIME)

---

## 📌 Note

This project was developed for educational purposes as part of my undergraduate coursework. It demonstrates the application of machine learning techniques for disease prediction and should not be considered a substitute for professional medical diagnosis or clinical decision-making.

---

## 👩‍💻 Author

**Aradhya Trehan**

Final Year B.E. Computer Science Engineering (Artificial Intelligence)

Interested in Data Analytics, Machine Learning, Business Analytics, and AI-driven solutions.
