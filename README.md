# Parkinson's Disease Detection using SVM

This project aims to build a machine learning model to detect Parkinson’s disease using clinical voice measurements. By analyzing vocal biomarkers, the model helps in early and non-invasive diagnosis of the disease.

## 🧠 Overview

Parkinson's disease affects the nervous system and leads to progressive movement disorders. Early detection can significantly improve treatment outcomes. This project uses Support Vector Machine (SVM) and various preprocessing techniques to classify whether a person has Parkinson's based on vocal features.

## 📊 Dataset

- Source: [Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- Size: 195 instances, 23 features
- Key feature: `status` (0 = healthy, 1 = Parkinson’s)

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## 🧪 Features & Steps

- Data preprocessing (handling missing values, scaling)
- Feature selection
- SVM classifier model
- Model evaluation using accuracy, confusion matrix
- Visualization of results

## ✅ Accuracy

Achieved an accuracy of **85–90%** on test data after hyperparameter tuning.

## 📁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Harshita-Tanwar/Parkinson_disease.git
   cd Parkinson_disease
