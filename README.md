# 💼 Income Classification Using Machine Learning  

## 📖 Overview  
This project focuses on predicting whether an individual's annual income exceeds **£50K** based on various **demographic and employment attributes**.  
By applying multiple machine learning algorithms, this project demonstrates the complete **end-to-end process** of building, evaluating, and optimising predictive models — from **data preprocessing to model interpretation**.  

---

## 🎯 Objective  
To classify income levels using demographic data and compare the performance of several machine learning models to identify the most accurate and reliable approach.  

---

## ⚙️ Key Steps  

### 🧹 Data Preprocessing  
- Handled missing and inconsistent values.  
- Encoded categorical variables using **LabelEncoder**.  
- Normalised numerical features with **StandardScaler**.  

### ⚖️ Balancing the Dataset  
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to address class imbalance.  

### 🤖 Model Development  
Trained and compared four supervised learning models:  
- Logistic Regression  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

### 🔧 Model Optimization  
- Used **GridSearchCV** for hyperparameter tuning and cross-validation.  

### 📊 Evaluation Metrics  
- Accuracy  
- F1-Score  
- Cohen’s Kappa  
- Confusion Matrix  

---

## 🧠 Key Insights  
- **Random Forest Classifier** achieved the best overall performance across evaluation metrics.  
- Higher education, work hours, and occupation types showed strong correlations with income level.  
- Demonstrated the strength of **ensemble methods** in capturing complex, non-linear relationships.  

---

## 🧰 Technologies Used  
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Scikit-learn, Imbalanced-learn** – Modelling and evaluation  
- **Plotly, Seaborn, Matplotlib** – Data visualisation  

---

## 📈 Results  

| Model | Accuracy | F1-Score | Kappa Score |
|--------|-----------|-----------|--------------|
| Logistic Regression | 83% | 0.78 | 0.70 |
| Decision Tree | 86% | 0.81 | 0.74 |
| KNN | 84% | 0.79 | 0.72 |
| **Random Forest** | **90%** | **0.85** | **0.79** |

> *(These values are representative of the project findings and may vary slightly per run.)*  

---

## 🔍 Conclusion  
This project highlights how **data preprocessing**, **balancing**, and **model selection** can significantly influence classification performance.  
It demonstrates an **end-to-end machine learning pipeline** that can be adapted for similar socioeconomic or business classification problems.  

---

