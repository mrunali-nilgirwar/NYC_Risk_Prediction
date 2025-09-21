# NYC Restaurant Risk Prediction
# NYC Restaurant Risk Prediction 🍽️

This project uses machine learning to predict **high-risk NYC restaurant inspections**.  
The goal is to help inspectors prioritize limited resources and improve food safety outcomes.

---

##  Dataset
- Source: [NYC Open Data – Restaurant Inspections](https://data.cityofnewyork.us/)  
- Features: cuisine type, borough, prior violations, inspection scores, etc.  
- Target: risk classification (high vs. low).

---

## Methodology
1. Data Cleaning & Preprocessing
   - Handled missing values, categorical encoding, outlier treatment.  
2. Exploratory Data Analysis (EDA)  
   - Visualized violations by cuisine, borough trends, risk distribution.  
3. Modeling   - Logistic Regression, Random Forest, XGBoost.  
   - Evaluation: accuracy, AUC, precision/recall.  
4. Explainability  
   - Feature importance & SHAP analysis for interpretability.  

---

##  Results
- Best model: **XGBoost** with AUC = `66.06` and Precision = `65.06%`.  
- Key drivers of high-risk classification: past violations, cuisine type, borough.  

---

## 🚀 How to Run
Clone the repo:
```bash
git clone https://github.com/mrunali-nilgirwar/NYC_Risk_Prediction.git
