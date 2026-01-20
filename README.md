# Predictive_Analytics_using_Stats

## Title
**Credit Card Fraud Detection Using Sampling Techniques and Machine Learning**

---

## Project Overview
This project aims to identify fraudulent credit card transactions by handling class imbalance using multiple sampling techniques. Various machine learning models are trained and evaluated to study how different sampling strategies influence prediction accuracy on an imbalanced dataset.

---

## Methodology

### Dataset Description
- The dataset contains credit card transaction records labeled as:
  - **0** → Non-Fraudulent Transaction  
  - **1** → Fraudulent Transaction
- The dataset is **highly imbalanced**, with fraudulent transactions forming a very small fraction of the total records.
- Such imbalance can cause machine learning models to become biased toward the majority class, making sampling techniques necessary.

---

### Sampling Techniques Implemented
To balance the dataset and enhance model performance, the following sampling methods were applied:

- **Simple Random Sampling**
- **Systematic Sampling**
- **Stratified Sampling**
- **Cluster Sampling**
- **Multistage Sampling**

---
## Machine Learning Models

Multiple classification models were trained on the sampled datasets to evaluate and compare their performance on fraud detection.

---

### Best Performing Model
Based on the accuracy comparison across all sampling techniques, the **RandomForestClassifier (M3)** consistently achieved the highest performance and demonstrated strong stability across different sampling methods.

---

### Highest Accuracy Achieved
- **100.0% accuracy**  
- Achieved using **RandomForestClassifier** with **Cluster Sampling**

---

## Input / Output Flow

### Input
- Credit Card Fraud Detection Dataset (CSV)

---

### Processing Steps
- Data Preprocessing  
- Application of Sampling Techniques  
- Machine Learning Model Training  
- Model Parameter Optimization  

---

### Output
- Balanced Datasets  
- Trained Classification Models  
- Accuracy Scores  
- Performance Comparison Table  
- Identification of the Best Model and Sampling Technique  

---

