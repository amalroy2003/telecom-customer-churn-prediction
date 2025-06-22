# 📊 Telecom Customer Churn Prediction

This project focuses on predicting *customer churn* in the telecom domain using machine learning techniques. The goal is to identify customers who are at high risk of leaving, helping businesses take preventive action and improve customer retention.

---

## 🔍 Problem Statement

Telecom companies often struggle with customer churn, which directly impacts their revenue and growth. By analyzing customer behavior and service-related attributes, we can build a model that predicts which customers are likely to discontinue their service, allowing for proactive retention strategies.

---

## 🧠 Project Highlights

- ✅ Exploratory Data Analysis (EDA)
- ✅ Data Cleaning & Preprocessing
- ✅ Feature Engineering
- ✅ Built a *Random Forest* classification model
- ✅ Evaluated the model using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
- ✅ Addressed class imbalance using stratified train-test split
- ✅ Interpreted results to understand churn-driving factors

---

## 📁 Project Structure

- Telecom_churn.ipynb – Jupyter Notebook with code, visualizations, and results
- customer_data.csv – Dataset used for training and evaluation
- output.html – HTML version of the notebook for quick reference

---

## 🔧 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Random Forest Classifier
- Jupyter Notebook

---

## 📈 Model Performance

The Random Forest model was evaluated on both training and testing data. Here's a summary of its performance:

### 🏋 Training Set:
- *Accuracy:* 87%
- *Precision:* 92% (Class 0), 84% (Class 1)
- *Recall:* 82% (Class 0), 93% (Class 1)
- *F1-Score:* 87% (Class 0), 88% (Class 1)

### 🧪 Test Set:
- *Accuracy:* 82%
- *Precision:* 86% (Class 0), 78% (Class 1)
- *Recall:* 77% (Class 0), 87% (Class 1)
- *F1-Score:* 81% (Class 0), 82% (Class 1)

### 📌 Insights:
- The model generalizes well with balanced metrics.
- High *recall* for churners on both training and test data is key for reducing false negatives.
- Performance is consistent, with no signs of major overfitting.

---

## 🚀 Future Enhancements

- Improve class balance handling using techniques like SMOTE or class weighting
- Add SHAP or LIME for explainable AI (feature importance insights)
- Deploy the model using Streamlit for user interaction
- Build an interactive dashboard for churn monitoring

---

## 👤 Author

*Amal Roy*  
📧 amal.roy2100@gmail.com](mailto:abdulrasheedj06@gmail.com)  
🔗 [GitHub](https://github.com/amalroy2003) | [LinkedIn](www.linkedin.com/in/amal-roy-e)
---

⭐ If you found this project useful, please give it a star!
