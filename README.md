#🔬 **Breast Cancer Classification with Neural Networks**

---

## 🧠 Overview

An interactive machine learning project developed in a **Jupyter Notebook**, using:

- **Pandas** for data manipulation  
- **Scikit-learn** (MLPClassifier) for neural network modeling  
- **Matplotlib/Seaborn** for visualization

🎯 The goal is to classify breast cancer tumors as **malignant** or **benign** using Neural Networks and analyze performance across different architectures.

---

## 🚀 Features

### 📥 Data Acquisition & Preprocessing
- Loads the **Breast Cancer Wisconsin (Diagnostic)** dataset
- Applies `StandardScaler` for robust feature scaling

### 🧠 Neural Network Modeling
- Implements **Multi-layer Perceptron (MLPClassifier)**  
- Tests various hidden layer configurations & learning rates  
- Tracks training and testing performance

### 📊 Model Evaluation
- Uses key metrics:
  - `accuracy_score`
  - `confusion_matrix`
  - `classification_report`

### 📈 Comparative Analysis
- Visualizes results to identify the best performing modelذ

---

## 📷 Preview

### Classification Report
![Model Classification Report](Classification_Report.png)

### Confusion Matrix  
![Best Model Confusion Matrix](Confusion_Matrix.png)

### ROC Curve   
![Best Model ROC Curve](ROC_Curve_Performance_Evaluation.png)

### Decision Boundary  
![Best Model Decision Boundary](Decision_Boundary.png)

### SVM Accuracy Comparison  
![Best Model SVM Accuracy Comparison](SVM_Accuracy_Comparison.png)

---

## ▶️ How to Run

- Make sure Python and Jupyter are installed on your system.

- Install dependencies 
  pip install -r requirements.txt

- Launch the notebook
  jupyter notebook Breast Cancer Classification.ipynb
