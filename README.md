# 🩺 Diabetes & Cardiovascular Health Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the likelihood of diabetes and cardiovascular-related health risks using machine learning classification models. The goal is to assist in early detection and support better healthcare decision-making.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Identify patterns and relationships in health data
* Build and evaluate multiple classification models
* Compare model performance using appropriate metrics
* Interpret results for real-world applications

---

## 📊 Dataset

* Publicly available dataset (Kaggle)
* Contains medical attributes such as:

  * Glucose level
  * Blood pressure
  * BMI
  * Age
  * Insulin level
* Target variable: **Outcome (0 = No Diabetes, 1 = Diabetes)**

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked dataset shape, structure, and summary statistics
* Identified missing values and duplicates
* Visualized:

  * Correlation heatmap
  * Feature distributions
  * Outliers using boxplots

---

## ⚙️ Data Preprocessing

* Feature-target separation
* Train-test split (80/20)
* Feature scaling using StandardScaler

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Random Forest Classifier**

---

## 📈 Model Evaluation

Models were evaluated using:

* ✅ Accuracy Score
* ✅ F1 Score
* ✅ Classification Report
* ✅ Confusion Matrix

---

## 📊 Results Summary

* Random Forest achieved the **highest performance**
* Logistic Regression provided good baseline results
* KNN performance depended on data scaling and parameter tuning

---

## 📉 Visualizations

* Confusion matrices (different color maps for each model)
* Feature importance graph (Random Forest)
* Model comparison graphs (Accuracy & F1 Score)

---

## 💡 Key Insights

* Glucose, BMI, and Age are strong predictors of diabetes
* Ensemble models (Random Forest) improve prediction accuracy
* Machine learning can support early disease detection

---

## 📁 Project Structure

```
├── Diabetes_&_Cardiovascular_Health_Prediction_Using_Machine_Learning_1.ipynb
├── diabetes_prediction_dataset.csv
├── README.md
```

---

## 🛠 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries
3. Open the notebook in Jupyter
4. Run all cells

---

## 👩‍💻 Author

**Chathumini Karunarathna**
Undergraduate – NSBM Green University

---

## ⭐ Acknowledgment

Dataset sourced from Kaggle for academic purposes.

---

## 📌 Conclusion

This project demonstrates how machine learning can be effectively applied in healthcare to predict diseases and improve early diagnosis, ultimately contributing to better patient outcomes.

