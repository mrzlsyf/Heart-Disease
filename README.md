# ❤️ Heart Disease 🎗️
This project leverages **Decision Tree and Support Vector Machine (SVM)** models to analyze key cardiovascular risk factors and provide interpretable insights for heart disease prediction.

---

## 📚 Project Naration
Cardiovascular disease (CVD) is the number one cause of death globally. It is estimated to claim the lives of around 18 million people each year or 31% of all deaths globally. Four out of five CVD deaths are caused by heart attacks and strokes, and a third are experienced prematurely in people under the age of 70.

Heart failure is one of the common causes of cardiovascular disease. As an associate data scientist, you are tasked with predicting the likelihood of heart disease. It is hoped that the resulting modelling can help doctors' performance in detecting patients with heart disease so that they can help more people who are at high risk of cardiovascular disease.

---

## 🎯 Overview
This project focuses on:
1. **Heart Disease Prediction** using **Decision Tree and SVM** models 🏥
2. **Feature Importance Analysis** to identify critical cardiovascular risk factors 🔍
3. **Interpretable Machine Learning Insights** to aid healthcare decision-making 📊

The goal is to create an **explainable and effective predictive model** that helps in identifying individuals at risk of heart disease, contributing to proactive healthcare strategies.

---

## 📂 Dataset
The dataset used in this project is **heart.csv**, which consists of several medical attributes used for heart disease classification, such as:
- **Age**
- **Sex**
- **Chest Pain Type (CP)**
- **Resting Blood Pressure (Trestbps)**
- **Cholesterol (Chol)**
- **Fasting Blood Sugar (FBS)**
- **Resting Electrocardiographic Results (Restecg)**
- **Maximum Heart Rate Achieved (Thalach)**
- **Exercise-Induced Angina (Exang)**
- **ST Depression Induced by Exercise (Oldpeak)**
- **Slope of the Peak Exercise ST Segment (Slope)**
- **Heart Disease Diagnosis (Target: 0 = No Disease, 1 = Disease)**

---

## 🏠 Project Workflow 📌
1. **Data Preprocessing & Cleaning** 🧹
   - Load dataset and handle missing values.
   - Perform feature scaling and encoding for categorical data.
2. **Exploratory Data Analysis (EDA)** 🔍
   - Visualize feature distributions and correlations.
   - Identify significant risk factors for heart disease.
3. **Model Training & Evaluation** 🏗️
   - Train **Decision Tree** and **SVM** models for classification.
   - Evaluate model performance using accuracy, precision, recall, and AUC-ROC.
4. **Feature Importance & Interpretability** 📈
   - Use Decision Tree feature importance ranking.
   - Analyze model insights for clinical interpretability.

---

## 📂 Project Structure 🛠️
```
📚 Heart-Disease-Prediction/
├── 📙 Heart Disease Predict.ipynb   # Jupyter Notebook for model training and analysis
├── 📗 heart.csv                     # Dataset containing patient heart health records
```

---

## ✨ Features
✅ **Predicts heart disease risk using Decision Tree and SVM models**  

✅ **Explores key cardiovascular risk factors through feature importance analysis**  

✅ **Provides interpretable machine learning insights for medical decision-making**  

✅ **Evaluates model performance with classification metrics and visualizations**  

---

## 🛠 Technologies & Libraries
🔹 **Python** 🐍  

🔹 **Pandas & NumPy** 📊  

🔹 **Scikit-Learn** 🤖 

🔹 **Matplotlib, Seaborn, Plotly** 🎨  

---

## 🚀 Installation
Ensure you have Python installed, then install dependencies:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn plotly
```

---

## 🎥 Usage
Run the Jupyter Notebook for data analysis and model training:
```sh
jupyter notebook "Heart Disease Predict.ipynb"
```

---

## 📊 Results
- **Identifies key features contributing to heart disease risk.**
- **Provides accurate predictive models using Decision Tree and SVM.**
- **Enhances medical decision-making with interpretable insights.**

---

## 🌟 Future Improvements
🌟 Implement **Deep Learning models** for enhanced accuracy.  

🌟 Optimize hyperparameters using **Grid Search or Random Search**.  

🌟 Extend dataset with **real-world clinical patient records**.  

---

## 🌍 Contributing
Contributions are welcome! Follow these steps to contribute:
1. **Fork the repository** 🌿  
2. **Create a new branch** 🌱  
3. **Make your changes** ✨  
4. **Submit a pull request** 🛠

*If you find this project useful, please **star ⭐ the repository** and share it with others!*  

---

>  **🏥 A healthy heart leads to a healthy life. Predicting risks early saves lives. 🚀🌟**
