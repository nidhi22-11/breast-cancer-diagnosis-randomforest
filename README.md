# Breast Cancer Diagnosis using Random Forest

This project implements a **machine learning model** to predict whether a tumor is **malignant or benign** using the **Wisconsin Breast Cancer Dataset**.  
The model is built with **Random Forest Classifier** and evaluated using multiple metrics including Accuracy, Precision, Recall, F1 Score, and ROC-AUC.

---

## 🧰 Technologies Used

- **Programming Language:** Python 3  
- **Libraries:**  
  - `pandas` for data handling  
  - `numpy` for numerical operations  
  - `scikit-learn` for machine learning  

---

## 💻 Project Overview

1. **Data Loading & Exploration**  
   - Load dataset and check for missing values  
   - Explore feature distributions  

2. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Encode categorical features (if present)  
   - Feature scaling (if needed)  

3. **Model Training**  
   - Train a Random Forest Classifier  
   - Use train-test split (or cross-validation)  

4. **Model Evaluation**  
   - Evaluate using **Accuracy, Precision, Recall Score**   

---

## 📊 Results

- **Accuracy:** ~0.92   
- **Precision:** ~0.89 
- **Recall:** ~0.88

> Values may vary depending on data split and random seed.

---

## 🔍 How to Run

1. Clone the repository:

```bash
git clone https://github.com/nidhi22-11/breast-cancer-diagnosis-randomforest.git
cd breast-cancer-diagnosis-randomforest

