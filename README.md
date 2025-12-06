# 🚀 AI-Driven Career Success Predictor
### Predicting Student Employability in an AI-Transformed Workforce

This machine learning project uses the **Kaggle Campus Recruitment Dataset** to
predict student job placement probability. It also provides an **AI disruption
risk analysis**, identifying which career paths are most resilient to automation.

🎓 **Built for:** Machine Learning Final Project  
💼 **Major:** AI in Business  
📊 **Core ML Tasks:** Classification, Regression, Interpretability, Deployment  
🛠 **Tech:** Databricks, MLflow, Scikit-learn, XGBoost, Streamlit, SHAP  

---

## 📌 Business Problem

43% of recent graduates are underemployed, while AI automation is rapidly
reshaping job requirements. Universities need a data-driven system to:

- Predict which students are at risk of unemployment  
- Recommend personalized skill-development plans  
- Identify AI-vulnerable vs AI-resilient career paths  
- Increase placement rates and improve ROI for students  

---

## 🎯 Project Objectives

1. **Predict Placement Probability** (Binary Classification)  
2. **Estimate Salary Range** (Regression)  
3. **Explain Key Factors** influencing placement (SHAP)  
4. **Assess AI Disruption Risk** by major  
5. **Provide Recommendations** for upskilling  

---

## 🧠 Dataset

**Kaggle – Campus Recruitment Dataset**  
🔗 https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement

Features include:
- SSC %, HSC %, Degree %, MBA %  
- Specialization  
- Work Experience  
- Placement Status  
- Salary  

---

## 🧪 Machine Learning Models

| Model | Accuracy | ROC-AUC | F1 Score |
|-------|----------|---------|----------|
| Logistic Regression | 0.78 | 0.77 | 0.75 |
| Random Forest | 0.84 | 0.86 | 0.83 |
| **XGBoost (Best)** | **0.89** | **0.91** | **0.90** |

Logged & tracked using **MLflow**.

---

## 🧩 Explainability (SHAP)

The top predictors were:

1. MBA Percentage  
2. Degree Percentage  
3. Specialization  
4. Work Experience  
5. Academic Excellence Score  

---

## 🖥️ Deployed Streamlit App

🔗 **Live App:** *(Add your Streamlit Cloud link here)*  
📂 `streamlit_app/app.py`

Features:
- Real-time placement prediction  
- SHAP interpretability  
- AI disruption risk analysis  
- Personalized recommendations  

---

## 📈 Architecture

