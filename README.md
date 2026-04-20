# 🎓 CGPA Prediction Model

This project focuses on predicting students' **CGPA** using machine learning techniques. The model is trained on academic-related features and evaluated using regression analysis to ensure accuracy and reliability.

---

## 📌 Overview

The goal of this project is to:

- Build a predictive model for CGPA  
- Analyze model performance using visualization techniques  
- Evaluate prediction accuracy and error distribution  

The results show strong alignment between predicted and actual CGPA values, indicating a well-performing model.

---

## ⚙️ Tech Stack

- Python 🐍  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📊 Model Performance

### 🔹 Predicted vs Actual
- Points closely follow the diagonal line  
- Indicates **high prediction accuracy**  
- Minimal deviation → low error  

### 🔹 Residual Analysis
- Errors are randomly scattered around zero  
- No visible pattern → **model is unbiased**  
- Slight spread at higher CGPA values suggests minor variability  

---
## 🚀 How to Run

1. Clone the repository:
  ```bash
git clone https://github.com/your-username/cgpa-prediction.git
cd cgpa-prediction

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook student.ipynb
