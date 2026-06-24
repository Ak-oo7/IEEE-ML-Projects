# 🛍️ Customer Segmentation Dashboard

A Machine Learning web application that segments mall customers based on **Annual Income** and **Spending Score** using clustering algorithms.

## 📌 Project Overview
Developed as part of the **IEEE AI/ML/DL Internship Program**.
Uses unsupervised learning to discover hidden customer groups, helping businesses apply targeted marketing strategies.

## 🤖 Algorithms Used
| Algorithm | Role |
|---|---|
| K-Means Clustering | Primary segmentation model |
| Hierarchical (Agglomerative) Clustering | Comparison model |

## ✨ Features
- 📂 Upload your own customer CSV
- 📊 Visualize customer clusters interactively
- 💰 Income vs Spending Score analysis
- 🔍 Per-segment business insights
- 📈 K-Means vs Hierarchical model comparison

## 🗂️ Project Structure
Customer_Segmentation/
├── app.py                    
├── requirements.txt              
├── Customer_Segmentation.ipynb  
├── dataset/
│   └── Mall_Customers.csv        
└── models/
└── kmeans_model.pkl         
## 🛠️ Tech Stack
`Python` · `Streamlit` · `Scikit-Learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SciPy` · `Joblib`

## ⚙️ How to Run
```bash
# From the root of the repo
cd Customer_Segmentation
pip install -r requirements.txt
streamlit run app.py
```
Then upload `dataset/Mall_Customers.csv` in the app interface.

## 📊 Dataset
**Mall Customer Segmentation Dataset**
- Features: `Annual Income (k$)`, `Spending Score (1-100)`
- Source: Kaggle
