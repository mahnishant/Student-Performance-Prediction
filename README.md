# Student Performance Prediction
This project uses **Linear Regression** to predict student academic performance based on features like hours studied, previous scores, and sleep hours.

## 📌 Project Overview

- Built a regression model using **scikit-learn** to predict the `Performance Index` of students.
- Achieved **R² score: 0.95**, **MAE: 2.16**, and **MSE: 7.29**.
- Explored the relationship between study habits and performance using EDA.

## 🧠 Features Used
- Hours Studied
- Previous Scores
- Extracurricular Activities (encoded)
- Sleep Hours
- Sample Question Papers Practiced

## 📊 Exploratory Data Analysis
- Correlation heatmaps and pairplots using **Seaborn**
- Scatter plots to visualize impact of features on performance
- Strong correlation found: `Hours Studied` → `Performance Index` (0.82)

## 🔧 Preprocessing Steps
- Removed duplicate entries
- Label encoded categorical features
- Handled missing values
- Train-test split (80/20)

## 🛠️ Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

## 📈 Model Evaluation Metrics
- R² Score: **0.95**
- MAE: **2.16**
- MSE: **7.29**

## 🚀 How to Run
1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

