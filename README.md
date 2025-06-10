# 🧠 Breast Cancer Prediction using Machine Learning

Welcome to the Breast Cancer Prediction project!  
This beginner-friendly project uses machine learning to predict whether a tumor is **malignant (M)** or **benign (B)** based on medical measurements from the Breast Cancer Wisconsin dataset.

---

## 🎯 Objective

Build a machine learning pipeline to:
- Analyze tumor features
- Predict cancer type (Malignant or Benign)
- Evaluate model performance

---

## 📁 Dataset

- File used: `Cancer_Data.csv`
- Source: Breast Cancer Wisconsin (Diagnostic) dataset
- Features: Mean values of radius, texture, perimeter, area, smoothness, etc.
- Target: Diagnosis (M = Malignant, B = Benign)

---

## 🚀 Workflow

1. **Data Loading**
2. **Exploratory Data Analysis**
3. **Data Cleaning & Preprocessing**
4. **Feature Scaling**
5. **Model Building (Logistic Regression & Random Forest)**
6. **Prediction & Evaluation**
7. **Real Input Testing**

---

## 📊 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn (Logistic Regression, RandomForest, Metrics)

---

## 📌 Results

| Model               | Train Accuracy | Test Accuracy |
|--------------------|----------------|---------------|
| Logistic Regression| ~97%           | ~94%          |
| Random Forest       | ~99%           | ~96%          |

> ✅ The Random Forest model showed better performance overall.

---

## 📦 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/breast-cancer-prediction.git
   cd breast-cancer-prediction
