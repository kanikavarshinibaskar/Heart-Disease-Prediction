# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Overview
Heart disease is one of the leading causes of death worldwide. Early prediction can help improve patient outcomes and reduce mortality. This project uses Machine Learning classification models to predict whether a patient is likely to have heart disease based on various medical parameters.

## 🎯 Objectives
- Develop a supervised machine learning model to predict heart disease.
- Compare the performance of multiple classification algorithms.
- Evaluate models using various performance metrics.
- Analyze important features contributing to heart disease prediction.

## 📂 Dataset
- **Dataset:** Heart Disease Dataset
- **Records:** 303
- **Features:** 13 input features + 1 target variable
- **Target:**
  - 0 → No Heart Disease
  - 1 → Heart Disease

## 🔧 Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 🤖 Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Multi-Layer Perceptron (MLP Classifier)

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curves

## 📈 Results

| Model | Accuracy |
|---------|---------|
| Random Forest | 83.61% |
| Logistic Regression | 80.33% |
| MLP Classifier | 72.13% |
| Decision Tree | 70.49% |

### Best Performing Model
✅ **Random Forest Classifier**
- Accuracy: **83.61%**
- Precision: **78.05%**
- Recall: **96.97%**
- F1 Score: **86.49%**

## 📊 Exploratory Data Analysis
- Distribution of Target Variable
- Age Distribution
- Correlation Heatmap
- Feature Importance Analysis

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── heart.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── correlation_heatmap.png
    ├── confusion_matrix.png
    └── roc_curve.png
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

## 🧪 Features Used

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- Slope
- Number of Major Vessels
- Thalassemia

## 📌 Conclusion

Among all the models implemented, the Random Forest Classifier achieved the best performance with an accuracy of **83.61%**. Due to its high recall and F1-score, it is well-suited for heart disease prediction and can assist healthcare professionals in early diagnosis and risk assessment.

## 👨‍💻 Author

**KANIKA VARSHINI S B**
- B.Tech Artificial Intelligence and Data Science
- Major Project: Heart Disease Prediction Using Machine Learning

## ⭐ If you found this project useful, please give it a star!
