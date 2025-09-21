# Full EDA | XGBoost

## Overview  
This notebook performs a **comprehensive Exploratory Data Analysis (EDA)** and builds a predictive model using **XGBoost**.  
The workflow covers:  
- Data exploration & visualization  
- Handling missing values and outliers  
- Feature engineering and preprocessing  
- Model training and evaluation with XGBoost  
- Insights from feature importance  

---

## Dataset  
- **Source:** Kaggle dataset (linked in the notebook)  
- **Rows & Features:** Tabular data with both numerical and categorical variables  
- **Target Variable:** Label column used for prediction  
- **Issues handled:** Missing values, class imbalance, outliers  

---

## Steps  

### 1. Exploratory Data Analysis (EDA)  
- Summary statistics of features  
- Visualizations of distributions and correlations  
- Outlier and imbalance detection  

### 2. Preprocessing & Feature Engineering  
- Missing value imputation  
- Encoding categorical variables  
- Feature scaling and transformations  
- Creation of new features (where relevant)  

### 3. Modeling with XGBoost  
- Train/test split  
- Model training and tuning  
- Evaluation using metrics such as accuracy, precision, recall, F1, ROC AUC  
- Feature importance analysis  

---

## Results  
- XGBoost provided strong predictive performance on the dataset  
- Key features driving predictions were identified via feature importance  
- Visual and statistical insights gained from EDA guided preprocessing decisions  

---

## How to Use  
1. Open the notebook on Kaggle: [Full EDA | XGBoost](https://www.kaggle.com/code/wafaaalayoubi/full-eda-xgboost)  
2. Run the cells step by step (EDA → preprocessing → modeling)  
3. Adjust dataset paths or hyperparameters if experimenting further  

---

## Requirements  
Main Python libraries used:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `xgboost`  

---