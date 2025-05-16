# -machine-learning-MRI-neuroimaging-classification-using-SVM-Random-Forest-XGBoost-and-KNN

# 🧠 MRI Neuroimaging Classification using SVM, Random Forest, XGBoost, and KNN

A high-performance, research-grade machine learning pipeline for **early dementia classification** from **MRI neuroimaging data**, utilizing classical supervised models (SVM, Random Forest, XGBoost, and KNN). The goal is to classify brain scans into one of four categories of cognitive impairment:

- Non-Demented
- Very Mild Dementia
- Mild Dementia
- Moderate Dementia

---

## 📌 Project Objectives

- Build a robust ML pipeline for multi-class classification using tabular and image-derived features.
- Benchmark SVM, Random Forest, KNN, and XGBoost models with rigorous cross-validation.
- Integrate multimodal MRI-derived features (texture, intensity, HOG, LBP, morphological).
- Provide explainable outputs and comparative analysis for clinical interpretability.

---

## 🗂️ Project Structure

## 🧪 Models Implemented

| Model         | Description |
|---------------|-------------|
| **SVM**       | Support Vector Machine with RBF kernel and soft margin tuning |
| **RandomForest** | Bagging-based ensemble with deep trees, leveraging Out-Of-Bag (OOB) estimates |
| **XGBoost**   | Gradient-boosted decision trees with early stopping and regularization |
| **KNN**       | Distance-based lazy learning algorithm with custom feature scalers |

---

## 📊 Features Extracted

MRI scans are converted to a structured feature vector using:

- **Histogram of Oriented Gradients (HOG)**
- **Local Binary Patterns (LBP)**
- **Intensity histograms (mean, std, entropy)**
- **Morphological features (volume, shape descriptors)**

---

## 🔍 Evaluation Metrics

- Accuracy, Precision, Recall, F1-Score (Macro & Per-Class)
- Confusion Matrix
- Class-wise ROC-AUC curves
- Radar chart of per-class F1 scores

---

Author

Developed by Kirubel Awoke
AI Researcher | Son of God 
leburikplc@gmail.com

This project is licensed under the MIT License.

any question email me.
