# 🎓 Student Performance Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-blue?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-blue?style=for-the-badge&logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 📌 Project Overview

This project is an **End-to-End Machine Learning Application** that predicts a student's **Math Score** based on demographic and academic information.

The project follows the complete Machine Learning lifecycle, including:

- Data Ingestion
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Model Selection
- Prediction Pipeline
- Flask Web Application Deployment

The objective is to demonstrate a production-ready ML workflow rather than simply training a machine learning model.

---

# 🚀 Features

- Complete End-to-End ML Pipeline
- Modular Project Structure
- Automatic Data Preprocessing
- Feature Scaling & Encoding
- Multiple Regression Models Comparison
- Best Model Selection
- Model Serialization using Pickle
- Flask Web Application
- Clean and Reusable Codebase

---

# 📂 Project Structure

```
Student_Performance/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   ├── test.csv
│   └── raw.csv
│
├── notebook/
│   ├── data/
│   ├── EDA STUDENT PERFORMANCE.ipynb
│   └── MODEL TRAINING.ipynb
│
├── src/
│   ├── components/
│   │     ├── data_ingestion.py
│   │     ├── data_transformation.py
│   │     └── model_trainer.py
│   │
│   ├── pipeline/
│   │     ├── predict_pipeline.py
│   │     └── train_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

# 📊 Dataset Information

The dataset contains information about students and their academic background.

### Input Features

- Gender
- Race / Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Reading Score
- Writing Score

### Target Variable

- Math Score

---

# 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset before model training.

The analysis includes:

- Missing Value Analysis
- Duplicate Value Check
- Data Type Inspection
- Feature Distribution
- Categorical Feature Analysis
- Numerical Feature Analysis
- Correlation Analysis
- Student Performance Analysis
- Average Score Analysis

---

# ⚙️ Data Preprocessing

The preprocessing pipeline performs:

### Numerical Features

- Median Imputation
- Standard Scaling

### Categorical Features

- Most Frequent Imputation
- One-Hot Encoding

A **ColumnTransformer** combines both preprocessing pipelines before model training.

---

# 🤖 Machine Learning Models Used

The following regression algorithms were trained and evaluated:

- Linear Regression
- Lasso Regression
- Ridge Regression
- K-Neighbors Regressor
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- CatBoost Regressor
- AdaBoost Regressor

---

# 📊 Model Performance

| Model | R² Score |
|--------|----------|
| Ridge Regression | **0.8806** |
| Linear Regression | **0.8792** |
| CatBoost Regressor | 0.8516 |
| Random Forest Regressor | 0.8523 |
| AdaBoost Regressor | 0.8420 |
| XGBoost Regressor | 0.8278 |
| Lasso Regression | 0.8253 |
| KNN Regressor | 0.7383 |
| Decision Tree | 0.7382 |

---

# 🏆 Best Model

After comparing multiple regression algorithms,

**Linear Regression** was selected as the final model because it achieved excellent predictive performance while maintaining simplicity and good generalization.

### Final Performance

- **R² Score : 87.92%**
- **RMSE : Low Prediction Error**
- **MAE : Low Absolute Error**

---

# 🧠 Machine Learning Workflow

```
Student Dataset
        │
        ▼
Data Ingestion
        │
        ▼
Data Transformation
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Best Model Selection
        │
        ▼
Save Model (.pkl)
        │
        ▼
Prediction Pipeline
        │
        ▼
Flask Web Application
```

---

# 💻 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-Learn
- CatBoost
- XGBoost
- Matplotlib
- Seaborn
- Flask
- Dill

---

# 🌐 Flask Web Application

The trained model is integrated into a Flask web application where users can:

- Enter student information
- Submit input
- Get predicted Math Score instantly

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/student-performance-prediction.git
```

Move into the project directory

```bash
cd student-performance-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

# 📷 Project Screenshots

Add screenshots here after uploading them.

Example:

```
images/
│
├── home_page.png
├── prediction_page.png
└── result_page.png
```

---

# 🚀 Future Improvements

- Hyperparameter Optimization
- Cross Validation
- Docker Deployment
- Cloud Deployment (AWS/Azure/GCP)
- CI/CD Pipeline
- Model Monitoring
- REST API
- Streamlit Dashboard

---

# 🎯 Learning Outcomes

This project helped in understanding:

- End-to-End Machine Learning Pipeline
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Model Selection
- Object-Oriented Programming
- Modular Project Structure
- Flask Deployment
- Production-Level ML Workflow

---

# 👨‍💻 Author

**Arpit Patel**

B.Tech Computer Science Engineering

Aspiring Machine Learning Engineer & Data Scientist


