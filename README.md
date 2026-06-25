# 🚀 Intelligent Feature Engineering and Selection

An end-to-end Machine Learning pipeline that performs **data preprocessing, automated feature engineering, feature selection, model benchmarking, and model explainability** using the California Housing dataset.

---

## 📌 Project Overview

This project demonstrates how AI can improve machine learning workflows by:

- Cleaning and preprocessing data
- Handling missing values
- Removing outliers
- Automatically generating new features
- Creating custom engineered features
- Selecting the most informative features
- Training multiple regression models
- Comparing model performance
- Explaining predictions using SHAP

---

## 📂 Workflow

### 1. Dataset Loading

- Loads the California Housing dataset
- Converts it into a Pandas DataFrame
- Adds the target column

---

### 2. Missing Value Simulation

Artificially introduces missing values into the dataset to simulate real-world scenarios.

---

### 3. Data Imputation

Uses **Median Imputation** with:

- `SimpleImputer`

to replace missing values.

---

### 4. Outlier Removal

Removes extreme values using the **Interquartile Range (IQR)** method.

---

### 5. Automated Feature Engineering

Uses **Featuretools Deep Feature Synthesis (DFS)** to automatically generate additional useful features.

---

### 6. Custom Feature Engineering

Creates domain-specific features such as:

- Income Per Room
- Occupancy Density

---

### 7. Feature Selection

Selects the top 10 important features using:

- `SelectKBest`
- `f_regression`

---

### 8. Model Training

Trains multiple regression models:

- Random Forest Regressor
- XGBoost Regressor

---

### 9. Model Evaluation

Evaluates each model using:

- R² Score
- Mean Absolute Error (MAE)

---

### 10. Feature Importance

Visualizes feature importance using:

- Random Forest Feature Importance

---

### 11. Explainable AI (XAI)

Uses **SHAP (SHapley Additive exPlanations)** to explain feature contributions for model predictions.

---

### 12. Final Report

Displays:

- Selected Features
- Benchmark Results
- Best Performing Model

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Featuretools
- XGBoost
- SHAP

---

## 📦 Installation

```bash
pip install pandas numpy matplotlib scikit-learn featuretools shap xgboost
```

---

## ▶️ Run the Project

```bash
jupyter notebook Intelligent_Feature_Engineering_And_Selection.ipynb
```

---

## 📊 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)

---

## 📈 Output

The notebook generates:

- Cleaned Dataset
- Engineered Features
- Selected Features
- Model Comparison Chart
- Feature Importance Plot
- SHAP Summary Plot
- AI Enhancement Report

---

## 📁 Project Structure

```
Intelligent_Feature_Engineering_And_Selection.ipynb
README.md
```

---

## 🎯 Key Features

- Automated Feature Engineering
- Feature Selection
- Missing Value Handling
- Outlier Detection
- Model Benchmarking
- Explainable AI with SHAP
- Regression Pipeline
- End-to-End Machine Learning Workflow

---

## 📚 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Additional Feature Selection Techniques
- More Regression Models
- Automated ML Pipeline
- Model Deployment

---

## 👨‍💻 Author

**Kinza Zahra**
