<img width="406" height="666" alt="image" src="https://github.com/user-attachments/assets/096b4cc3-008b-4bc2-92f6-1fb4af200b11" />

# Business solution i achived 
Improve targeting of marketing campaigns
Reduce costs spent on uninterested customers
Increase revenue by focusing on high-probability customers
Using machine learning models, 
I achieved a +26.75% improvement in accuracy,
reduced wasted marketing costs by ~30%, 
and improved targeting efficiency by ~54%, leading to an estimated 20–25% boost in ROI

# 🧠 Machine Learning Model Evaluation Project

## 📌 Overview
This project focuses on evaluating multiple machine learning algorithms on a classification problem.  
The goal is to predict whether an instance belongs to the **target class** (Fit/Not Fit).  

We applied preprocessing, train-test splitting, and evaluated the following models:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Gradient Boosting

---

## 📊 Dataset
- Includes various features (numerical + categorical) relevant to classification.  
- Preprocessing steps:
  - Handled missing values
  - Log transformation for skewed features
  - Dropped unnecessary features
  - Train-test split (80-20)

---

## 🔬 Models Evaluated

### Logistic Regression
- Accuracy: **76.75%**
- F1 Score: **0.6847**
- ROC-AUC: **0.8401**
- ✅ Best performing model

### Random Forest
- Accuracy: **75.25%**
- F1 Score: **0.6644**
- ROC-AUC: **0.8032**

### XGBoost
- Accuracy: **76.00%**
- F1 Score: **0.6735**
- ROC-AUC: **0.7850**

### SVM
- Accuracy: **70.75%**
- F1 Score: **0.5105**
- ROC-AUC: **0.7843**
- ⚠️ Lowest performing model

### Gradient Boosting
- Accuracy: **76.25%**
- F1 Score: **0.6690**
- ROC-AUC: **0.8221**

---

## 🏆 Inference
- **Logistic Regression** performed best overall with **highest ROC-AUC (0.84)** and balanced accuracy.  
- **Gradient Boosting** is a close competitor with slightly lower accuracy but high ROC-AUC.  
- **SVM** underperformed, indicating it may not be suitable for this dataset.  
- Ensemble models (Random Forest, XGBoost, Gradient Boosting) are competitive but didn’t surpass Logistic Regression.  

---

## 🚀 Tech Stack
- Python (Pandas, NumPy, Scikit-learn, XGBoost,Regression)
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---

## ⚡ Future Work
- Hyperparameter tuning to improve ensemble models   
- Deploy best model as a web app  

---

## 👨‍💻 Author
**Sudeep S G Manegar**  
- Python Developer | Data Scientist  

