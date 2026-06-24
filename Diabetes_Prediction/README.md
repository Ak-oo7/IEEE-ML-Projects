# 🩺 Diabetes Risk Prediction Web Application

A Machine Learning web application that predicts whether a patient is at **risk of diabetes** based on clinical health parameters.

## 🚀 Live Application
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://diabetespredictiongit-inql8uanwywdaxkf5wwjnb.streamlit.app)

👉 **[Open Live App](https://diabetespredictiongit-inql8uanwywdaxkf5wwjnb.streamlit.app)**

## 📌 Project Overview
Developed as part of the **IEEE AI/ML/DL Internship Program**.
Predicts diabetes risk using a trained classification model, with a probability score, risk level meter, and health recommendations.

## 📥 Input Parameters
| Parameter | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| Blood Pressure | Diastolic blood pressure (mm Hg) |
| Skin Thickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body mass index |
| Diabetes Pedigree Function | Genetic likelihood score |
| Age | Age in years |

## 📤 Output
- ✅ Diabetes Risk Prediction (Diabetic / Non-Diabetic)
- 📊 Probability Score
- 🔴 Risk Level Meter
- 💊 Personalized Health Recommendations
- 📈 BMI Category Analysis

## 🤖 Model Performance
| Model | Accuracy |
|---|---|
| **Logistic Regression** ✅ | **76.62%** |
| Random Forest Classifier | 75.97% |

**Selected:** Logistic Regression — highest accuracy on the test set.

## 🗂️ Project Structure
```
Diabetes_Prediction/
├── app.py                       # Streamlit web application
├── requirements.txt             # Python dependencies
├── dataset/
│   └── diabetes.csv             # Pima Indians Diabetes Dataset
├── models/
│   ├── diabetes_model.pkl       # Trained Logistic Regression model
│   └── scaler.pkl               # Feature scaler
└── notebooks/
    └── diabetes_analysis.ipynb  # EDA + model training notebook
```
## 🛠️ Tech Stack
`Python` · `Streamlit` · `Scikit-Learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Joblib`

## ⚙️ How to Run
```bash
cd Diabetes_Prediction
pip install -r requirements.txt
streamlit run app.py
```

## 📊 Dataset
**Pima Indians Diabetes Dataset**
- 768 patient records
- Target: `Outcome` — 0 = Non-Diabetic, 1 = Diabetic
