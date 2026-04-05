# 🫀 Heart Disease Prediction Model

A machine learning classification project that predicts the likelihood of heart disease in patients using structured clinical data. Built to demonstrate end-to-end ML pipeline development — from raw data preprocessing to optimized model deployment.

---

## 📌 Problem Statement

Heart disease is one of the leading causes of mortality worldwide. Early and accurate prediction can assist healthcare professionals in identifying high-risk patients and taking preventive action. This project frames the problem as a binary classification task using real-world clinical features.

---

## 🚀 Key Features

- End-to-end ML pipeline: data cleaning → preprocessing → model training → evaluation
- Compared multiple classification algorithms to identify the best performer
- Hyperparameter tuning using GridSearchCV for optimal results
- Achieved **~88% F1-score** on test data

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| ML Library | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |

---

## 📊 Dataset

- **Source:** UCI Heart Disease Dataset (Cleveland)
- **Features:** Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, ECG results, Max Heart Rate, Exercise Induced Angina, ST Depression, Slope, Major Vessels, Thalassemia
- **Target:** Binary (0 = No Disease, 1 = Disease Present)

---

## ⚙️ ML Pipeline

```
Raw Data
   ↓
Exploratory Data Analysis (EDA)
   ↓
Preprocessing (Encoding, Feature Scaling, Missing Value Handling)
   ↓
Model Training (KNN vs Random Forest)
   ↓
Hyperparameter Tuning (GridSearchCV)
   ↓
Evaluation (F1-Score, Accuracy, Confusion Matrix)
```

---

## 📈 Results

| Model | F1-Score |
|---|---|
| K-Nearest Neighbors (KNN) | ~83% |
| Random Forest (Tuned) | **~88%** |

Random Forest with GridSearchCV tuning outperformed KNN across all evaluation metrics.

---

## 📁 Project Structure

```
Heart-Disease-Prediction-ml/
│
├── data/
│   └── heart.csv
├── notebook/
│   └── heart_disease_prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🔧 How to Run

```bash
# Clone the repository
git clone https://github.com/mittal-2004/Heart-Disease-Prediction-ml.git
cd Heart-Disease-Prediction-ml

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebook/heart_disease_prediction.ipynb
```

---

## 🧠 Key Learnings

- Importance of feature scaling for distance-based models like KNN
- How GridSearchCV systematically finds optimal hyperparameters
- Trade-offs between model interpretability and performance
- Using F1-score as the primary metric for imbalanced medical datasets

---

## 👤 Author

**Manav Mittal**
- LinkedIn: [linkedin.com/in/manav-mittal72](https://linkedin.com/in/manav-mittal72)
- Email: manavmittal1104@gmail.com
