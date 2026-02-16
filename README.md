# admission-chance-prediction-ml

# 🎓 Ivy League Admission Predictor (Machine Learning)

This project predicts the **chance of admission to Ivy League universities** using Machine Learning based on a student’s academic and profile features such as **GRE, TOEFL, CGPA, SOP, LOR, Research experience, and University Rating**.

## 🚀 Project Objective
To build a regression-based ML model that estimates a student’s **probability of getting admitted** to top universities by analyzing historical admission data.

## 📊 Dataset
The dataset contains **500 student profiles** with features related to academic performance and profile strength.  
There are **no missing values or duplicates** in the dataset.

## 🔍 Exploratory Data Analysis (EDA)
- Performed correlation analysis to understand relationships between features and admission chances.  
- Observed strong positive correlation for **CGPA, GRE, and TOEFL** with the target variable (*Chance of Admit*).

## 🛠️ Feature Engineering
- Created new features to capture combined effects:
  - `Overall_Score = GRE + TOEFL`
  - `SOP_LOR_Interaction = SOP × LOR`

## ⚙️ Multicollinearity Handling
- Used **Variance Inflation Factor (VIF)** to detect highly correlated features.  
- Reduced redundancy by removing highly collinear variables to improve model stability and interpretability.

## 🤖 Model Used
- **Linear Regression** (Supervised Learning – Regression)
- Used to predict continuous output: *Chance of Admit (0–1)*

## 📈 Model Evaluation
- **Train-Test Split:** 80% training, 20% testing  
- **Metrics Used:**
  - R² Score  
  - RMSE (Root Mean Squared Error)

## 🧠 Key Learnings
- How to perform EDA and correlation analysis  
- Importance of feature engineering in ML projects  
- Handling multicollinearity using VIF  
- Building and evaluating regression models  
- Interpreting model coefficients and predictions  

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Statsmodels  

## 📌 Use Case
This project can help students get an **estimated idea of their admission chances** and understand which factors influence admissions the most.

## 📷 Sample Visualizations
- Correlation heatmap  
- TOEFL vs University Rating boxplot  
- GRE vs Research boxplot  
- CGPA vs Chance of Admit scatter plot  

## 🔗 Author
**Ajay **  
LinkedIn: *linkedin.com/in/ajay-ponnuru*  

