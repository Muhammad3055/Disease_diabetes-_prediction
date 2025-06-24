# 🩺 Disease Diagnosis Prediction using Machine Learning

This project aims to build a medical prediction model that can help in the **early detection of diseases** such as **diabetes** and **heart disease** using machine learning techniques.

## 📊 Dataset
- **PIMA Indians Diabetes Dataset** (768 samples, 8 features)
  - Source: [Kaggle Link](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Optionally: [Heart Disease UCI Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

## 🧠 Objectives
- Perform **Exploratory Data Analysis** (EDA)
- Select & scale features to improve model performance
- Train and evaluate ML models: **Gradient Boosting**, **SVM**, and **Neural Networks**
- Use metrics like **F1 Score** and **AUC-ROC** for evaluation
- Provide **clinically actionable insights**

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, Matplotlib, Seaborn
- Streamlit (optional for deployment)

## 🧪 Models Used
| Model | Accuracy | F1-Score | AUC-ROC |
|-------|----------|----------|----------|
| Gradient Boosting | ✅ High | ✅ Balanced | ✅ Excellent |
| SVM | ✅ Robust | ✅ Good | ✅ Stable |
| Neural Network | ✅ Adaptive | ✅ Good | ✅ Learning-dependent |

## 📈 Evaluation Metrics
- **F1 Score** for handling class imbalance
- **ROC-AUC Curve** for performance visualization
- **Confusion Matrix** for class-wise diagnosis

## 🔬 Insights for Healthcare Professionals
- High-risk indicators: **Glucose**, **BMI**, and **Age**
- Helps in identifying early-stage diabetes risk
- Can be used as a **screening tool** in remote or under-resourced settings

## 🚀 How to Run
```bash
pip install -r requirements.txt
python disease_diabetes_prediction.py
