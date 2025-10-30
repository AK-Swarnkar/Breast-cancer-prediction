<!-- Project Banner -->
<p align="center">
  <img src="https://raw.githubusercontent.com/abhaykumar/breast-cancer-ml/main/assets/banner.png" alt="Breast Cancer Detection Banner" width="100%">
</p>

<h1 align="center">🧠 Breast Cancer Detection using Machine Learning</h1>

<p align="center">
  <b>Predicting breast cancer using supervised machine learning techniques for early diagnosis and better healthcare outcomes.</b>
</p>

---

## 📘 Overview

Breast cancer is one of the most common cancers in women worldwide.  
This project uses **Machine Learning** models to classify whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on diagnostic features.

The goal is to assist in **early detection** — improving patient outcomes through data-driven insights.

---

## ⚙️ Project Workflow

1. **Data Collection**  
   → Used the **Breast Cancer Wisconsin (Diagnostic) Dataset** from `sklearn.datasets`.

2. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling using `StandardScaler`  
   - Splitting data into training and test sets  

3. **Model Training**  
   Trained and compared multiple ML models:
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest  
   - Support Vector Machine (SVM)  
   - K-Nearest Neighbors (KNN)

4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix and ROC Curve  

5. **Deployment (Optional)**  
   - Model serialized using `joblib`  
   - Web app built using **Streamlit / Flask**

---

## 🧩 Dataset Information

| Feature | Description |
|----------|--------------|
| mean radius | Mean of distances from center to points on the perimeter |
| mean texture | Standard deviation of gray-scale values |
| mean smoothness | Local variation in radius lengths |
| ... | ... |
| target | 0 = malignant, 1 = benign |

📊 **Total Samples:** 569  
🧠 **Features:** 30  

---

## 🧠 Model Performance

<p align="center">
  <img src="https://raw.githubusercontent.com/abhaykumar/breast-cancer-ml/main/assets/confusion_matrix.png" alt="Confusion Matrix" width="70%">
</p>

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| Logistic Regression | 98.2% | 97.8% | 98.1% | 97.9% |
| Random Forest | 97.3% | 96.9% | 97.1% | 97.0% |
| SVM | 98.5% | 98.3% | 98.6% | 98.4% |

---

## 🚀 Getting Started

### 🔧 Requirements
```bash
pip install numpy pandas matplotlib scikit-learn seaborn
