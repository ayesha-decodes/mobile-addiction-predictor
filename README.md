# 📱 Smartphone Usage & Behavioral Addiction Prediction

A Machine Learning project that analyzes smartphone usage behavior and predicts whether a user is **Addicted** or **Not Addicted** using classification algorithms.

---

## 📖 Project Overview

Smartphone addiction has become a growing concern due to excessive screen time and digital engagement. This project performs **Exploratory Data Analysis (EDA)** on smartphone usage data and builds a **Random Forest Classifier** to predict whether a user is addicted based on their smartphone usage patterns.

The project follows a complete Machine Learning workflow including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Model Building
- Model Evaluation
- Prediction

---

## 🎯 Objectives

- Analyze smartphone usage behavior
- Perform Exploratory Data Analysis
- Identify important factors contributing to addiction
- Train a Machine Learning model
- Predict whether a user is addicted or not
- Evaluate model performance using various metrics

---

## 📂 Dataset

The dataset contains information about smartphone usage behavior and addiction.

### Features include:

- Daily Screen Time
- App Sessions
- Social Media Usage
- Gaming Time
- Notifications
- Night Usage
- Age
- Work/Study Hours
- Stress Level
- Apps Installed

### Target Variable

| Value | Description |
|--------|-------------|
| addicted | User is addicted |
| not addicted | User is not addicted |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The notebook performs:

- Dataset Overview
- Data Types
- Statistical Summary
- Missing Value Analysis
- Duplicate Detection
- Target Variable Distribution
- Histograms
- Correlation Heatmap
- Boxplots
- Feature Analysis

---

## 🤖 Machine Learning Pipeline

```
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Selection
      │
      ▼
Train-Test Split
      │
      ▼
Random Forest Classifier
      │
      ▼
Model Evaluation
      │
      ▼
Prediction
```

---

## 📈 Model Used

- Random Forest Classifier

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Feature Importance

---

## 📷 Visualizations

The notebook generates:

- 📊 Target Distribution
- 📈 Histograms
- 🔥 Correlation Heatmap
- 📦 Boxplots
- 🌲 Feature Importance
- ✅ Confusion Matrix
- 📉 ROC Curve

---

## 📁 Project Structure

```
Smartphone-Addiction-Prediction/
│
├── mobile_addiction.csv
├── Smartphone_Addiction_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/ayesha-decodes/Smartphone-Addiction-Prediction.git
```

Go to the project folder

```bash
cd Smartphone-Addiction-Prediction
```

Install required libraries

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook

```bash
jupyter notebook
```

---

## ▶️ How to Run

1. Open the notebook.
2. Load the dataset.
3. Run each notebook cell sequentially.
4. Train the Random Forest model.
5. Evaluate model performance.
6. Predict addiction status for new users.

---

## 📌 Example Prediction

### Input

```python
new_user = {
    "daily_screen_time": 8,
    "app_sessions": 85,
    "social_media_usage": 5,
    "gaming_time": 3,
    "notifications": 120,
    "night_usage": 4,
    "age": 22,
    "work_study_hours": 5,
    "stress_level": 8,
    "apps_installed": 60
}
```

### Output

```
Prediction : Addicted

Probability

Addicted      : 91.4%
Not Addicted  : 8.6%
```

---

## 📊 Results

The Random Forest model provides accurate predictions for smartphone addiction by learning behavioral usage patterns.

The project also identifies the most important features contributing to smartphone addiction using feature importance analysis.

---

## 🔮 Future Improvements

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost
- LightGBM
- Hyperparameter Tuning
- Cross Validation
- Streamlit Web App
- Flask/FastAPI Deployment
- Deep Learning Models

---

## 📚 Learning Outcomes

This project demonstrates:

- Data Cleaning
- Data Visualization
- Exploratory Data Analysis
- Feature Engineering
- Classification Models
- Model Evaluation
- Predictive Analytics

---

## 📌 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Install using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## 👩‍💻 Author

**Ayesha Nagma**

- Python
- Machine Learning
- Data Science
- SQL
- Data Analytics

---

## ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star** on GitHub.

It helps others discover the project and supports future improvements.
