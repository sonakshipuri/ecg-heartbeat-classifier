# ECG Signal Classification using Machine Learning

## Overview
This project classifies ECG heartbeat signals into normal and abnormal categories using machine learning. It covers the complete pipeline from preprocessing to model evaluation.

## Dataset
- https://www.kaggle.com/datasets/shayanfazeli/heartbeat
- **Source:** MIT-BIH Arrhythmia Dataset  
- **Classes:**
  - Normal  
  - Supraventricular  
  - Ventricular  
  - Fusion  
  - Unknown  

## Workflow

### 🔹 Data Loading
- Load train/test CSV files
- Split features and labels

### 🔹 Exploratory Data Analysis (EDA)
- Class distribution visualization  
- Raw ECG signal plots  
- Average waveform per class  

### 🔹 Preprocessing
- MinMax Scaling  
- Handling class imbalance  

### 🔹 Feature Extraction
Extracted statistical features:
- Mean, Std, Min, Max  
- Median, Variance  
- Skewness, Kurtosis  
- Energy, Peak metrics  

## Models Used
- Logistic Regression  
- Random Forest (features-based)  
- Random Forest (raw signals)  
- XGBoost  

## Evaluation Metrics
- Accuracy  
- Macro F1 Score  
- ROC-AUC  
- Confusion Matrix  

## Key Insights
- Tree-based models outperform linear models  
- Raw ECG signals perform better than extracted features  
- XGBoost achieved the best results  
- Macro F1 is important due to class imbalance  

## Tech Stack
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

