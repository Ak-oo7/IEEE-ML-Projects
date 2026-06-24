# 💰 Data Science Salary Predictor

A Machine Learning-powered web application that predicts Data Science salaries based on experience level, employment type, job title, remote work ratio, company size, and work year.

## 📌 Project Overview

This project uses a trained Random Forest Regression model to estimate annual salaries for Data Science professionals. The application provides salary predictions along with monthly and weekly salary breakdowns through an interactive Flask web interface.

## 🚀 Features

- 💼 Predict salaries for Data Science roles
- 📊 Annual, Monthly, and Weekly salary estimates
- 🌍 Supports remote and on-site work scenarios
- 🏢 Company size impact analysis
- 🎯 Random Forest Regression model
- 🌐 Responsive Flask web application
- 📈 Exploratory Data Analysis visualizations

---

## 🤖 Machine Learning Model

| Component | Description |
|------------|------------|
| Algorithm | Random Forest Regressor |
| Dataset | Data Science Salaries Dataset |
| Target Variable | Salary in USD |
| Framework | Scikit-Learn |
| Backend | Flask |

---

## 📥 Input Parameters

| Parameter | Description |
|------------|------------|
| Work Year | Year of employment |
| Experience Level | Entry, Mid, Senior, Executive |
| Employment Type | Full-time, Part-time, Contract, Freelance |
| Job Title | Data Science related position |
| Remote Ratio | Percentage of remote work |
| Company Size | Small, Medium, Large |

---

## 📤 Output

The model predicts:

- 💰 Annual Salary
- 📅 Monthly Salary
- 📆 Weekly Salary

Example:

```json
{
  "annual": 145000,
  "monthly": 12083,
  "weekly": 2788
}
```

---

## 📂 Project Structure

```text
Salary_Predictor/
│
├── app.py
├── project_ml.ipynb
├── requirements.txt
├── README.md
│
├── ds_salaries.csv
│
├── salary_model.pkl
├── scaler.pkl
├── label_encoders.pkl
├── feature_names.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
├── actual_vs_predicted.png
├── eda_jobs.png
├── eda_salary.png
└── feature_importance.png
```

---

## 🛠️ Tech Stack

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- Joblib
- HTML
- CSS
- JavaScript

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/Ak-oo7/IEEE-ML-Projects.git
cd IEEE-ML-Projects/Salary_Predictor
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Application

```bash
python app.py
```

### 4. Open Browser

```text
http://127.0.0.1:5000
```

---

## 📊 Dataset

**Data Science Salaries Dataset**

Contains information about:

- Data Science job roles
- Experience levels
- Employment types
- Company sizes
- Remote work ratios
- Salaries in USD

---

## 📈 Exploratory Data Analysis

The project includes:

- Salary distribution analysis
- Job title frequency analysis
- Feature importance visualization
- Actual vs Predicted salary comparison

---

## 🔗 API Endpoints

### Health Check

```http
GET /health
```

Response:

```json
{
  "model_loaded": true
}
```

### Salary Prediction

```http
POST /predict
```

Returns salary predictions based on user inputs.

---

## 👨‍💻 Author

**Ak-007**

Machine Learning Project developed as part of AI/ML learning and portfolio development.

GitHub: https://github.com/Ak-oo7
