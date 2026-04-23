# 📊 Employee Attrition & Financial Impact Analysis

## 📌 Overview
This project uses machine learning to analyze employee attrition and estimate its financial impact on organizations. It combines classification and regression models to predict employee turnover and quantify potential losses.

## 🎯 Objectives
- Predict employee attrition (Classification)
- Estimate future salaries of likely-to-stay employees (Regression)
- Calculate expected financial loss due to attrition

## 📂 Dataset
- IBM HR Analytics Attrition Dataset (Kaggle)

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 🧹 Data Preprocessing
- Label Encoding for categorical variables
- Feature Scaling using StandardScaler
- Simulated future salary based on performance ratings

## 🤖 Models Used

### 🔹 Classification (Attrition Prediction)
- Logistic Regression (Best Model)
- Decision Tree
- Support Vector Classifier (SVC)

Performance:
- F1 Score: 0.503
- AUC-ROC: 0.796
- Recall: 0.766

### 🔹 Regression (Future Salary Prediction)
- Random Forest Regressor (Best Model)
- Ridge Regression
- Lasso Regression
- Support Vector Regressor (SVR)

Performance (Random Forest):
- R² Score: 0.9999
- RMSE: 30.54

## 💰 Financial Impact Calculation

Expected Loss per Employee:
Expected Loss = P(Attrition) × Predicted Future Salary


## 📈 Key Insights
- Logistic Regression provides interpretable attrition predictions
- Random Forest captures complex salary patterns effectively
- High recall ensures most at-risk employees are identified
- Quantifies business impact of employee turnover

## 🚀 Future Improvements
- Add more features (bonuses, performance history)
- Improve interpretability using SHAP
- Use ensemble stacking for better accuracy

## 🧠 Conclusion
This project bridges data science and HR analytics by enabling organizations to identify attrition risks and estimate their financial impact, supporting smarter retention strategies.
