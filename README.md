<div align="center">

# 🩺🤖 DOCTOR JEN-AI  
### Heart Disease Prediction System  
*DATA 602 – Final Project Tutorial*

<a href="https://esingh16.github.io/Doctor-JEN-AI/"><b>🌐 Live Tutorial</b></a>

<br/>

<img src="./images/beat.gif" alt="Heartbeat Animation" width="420"/>

<br/>

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green)
![Course](https://img.shields.io/badge/Course-DATA%20602-orange)

</div>

---

## 📌 Overview
Heart disease is a major global health concern.  
This project presents an **end-to-end machine learning system** that predicts the **presence of heart disease** using patient clinical data.

The tutorial demonstrates how **exploratory analysis, statistical testing, and machine learning** can be combined to produce **accurate, interpretable, and clinically meaningful insights**.

---

## 👥 Team
- **Eshan Singh** (UID: 122115569)  
- **Nicole Miranda** (UID: 116014687)  
- **Jamiya Kirkland** (UID: 122328396)

---

## 🎯 Problem Definition
The goal is to predict whether a patient has heart disease (`0 = No`, `1 = Yes`) based on clinical attributes such as heart rate, cholesterol, chest pain type, and ECG measurements.

**Objectives:**
- Build a complete **data science pipeline**
- Apply **EDA and statistical inference**
- Train and compare **multiple ML models**
- Emphasize **interpretability and insights**, not just accuracy

---

## 📂 Dataset
- **Source:** UCI Machine Learning Repository  
  https://archive.ics.uci.edu/dataset/45/heart+disease

**Dataset Characteristics:**
- Real-world clinical heart disease data  
- Mixed numerical and categorical features  
- Binary classification target  

---

## 🧠 Model Architecture Diagram
<p align="center">
  <img src="images/heartfinal.png" width="650" alt="Model Architecture Diagram">
</p>

This diagram illustrates the **full project pipeline** from raw data ingestion to model evaluation and interpretation.

---

## 🔧 Data Preparation
The dataset was cleaned and prepared using the following steps:
- Renamed columns for better interpretability  
- Handled missing values  
- Corrected data types  
- Removed duplicate records  
- Applied feature scaling where required  

> All preprocessing steps are shown **explicitly in code** to ensure reproducibility.

---

## 📊 Exploratory Data Analysis (EDA)

<p align="center">
  <img src="images/histogram.png" width="750">
</p>

<p align="center">
  <img src="images/piechart.png" width="750">
</p>

<p align="center">
  <img src="images/heatmap.png" width="750">
</p>

<p align="center">
  <img src="images/boxplot.png" width="750">
</p>

EDA focuses on **visual understanding** of the data and includes:
- Target class distribution  
- Feature histograms and boxplots  
- Correlation heatmap  
- Clinical interpretation of **maximum heart rate** and **ST depression**

---

## 📐 Statistical Analysis

<p align="center">
  <img src="images/chisquare.png" width="650">
</p>

<p align="center">
  <img src="images/pairwise.png" width="750">
</p>

To support EDA findings, we apply:
- Correlation analysis  
- Independent **t-tests** for numerical variables  
- **Chi-square tests** for categorical variables  

These tests help distinguish **statistical association** from **predictive importance**.

---

## 🤖 Machine Learning Models
The following models are implemented and compared:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest**
- **Support Vector Machine (SVM)**

Each model follows a consistent:
- Train/test split  
- Evaluation metric strategy  
- Visualization pipeline  

---

## 📈 Model Performance & Visualization

### ROC Curve Comparison
<p align="center">
  <img src="images/roc.png" width="750">
</p>

### Decision Tree Feature Importance
<p align="center">
  <img src="images/dt.png" width="650">
</p>

### Decision Boundary Visualization
<p align="center">
  <img src="images/boundary.png" width="650">
</p>

Evaluation includes:
- Accuracy, Precision, Recall, and F1-score  
- ROC curves and AUC  
- Feature importance for tree-based models  
- Overfitting analysis across different tree depths  

---

## 🔍 Inference
The trained models can be used to **infer heart disease risk for new patient records** by passing clinical attributes through the final trained pipeline.

This demonstrates how machine learning systems can support **clinical decision-making**, while emphasizing that these models are **assistive tools**, not replacements for professional medical diagnosis.

---

## 🧠 Insights & Conclusions
- **Maximum heart rate** and **ST depression** consistently emerge as the strongest predictors  
- Some features show statistical significance but limited multivariate impact  
- **Logistic Regression** provides strong performance with high interpretability  
- **Decision Trees** capture non-linear patterns but may overfit at higher depths  
- Combining **EDA, statistics, and ML** leads to more reliable and explainable predictions  

✔ A non-technical reader gains medical insight  
✔ A technical reader gains modeling insight  

---

## 🛠️ Tools & Libraries
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
