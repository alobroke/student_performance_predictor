# 🎓 Student Performance Predictor (End-to-End ML Project)

An end-to-end Machine Learning project that predicts student academic performance based on demographic and educational features. This project demonstrates a **production-ready ML pipeline**, including data ingestion, preprocessing, model training, and deployment using a Flask web application.

---

## 🚀 Project Overview

This project aims to predict a student's **math score** using features such as gender, parental education, lunch type, and test preparation status.

It follows a **modular and scalable architecture** similar to industry ML systems:

* Data Ingestion
* Data Transformation
* Model Training
* Prediction Pipeline
* Web Deployment (Flask)

---

## 🧠 Problem Statement

Educational institutions can benefit from predictive insights into student performance. This system helps:

* Identify students at risk
* Support data-driven decision-making
* Improve academic outcomes

---


## 📂 Project Structure

```
student-performance/
│
├── artifacts/                # Saved model & preprocessor
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── src/
│   ├── components/           # Data ingestion, transformation, training
│   ├── pipeline/             # Prediction pipeline
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/                # HTML frontend
├── app.py                    # Flask application
├── requirements.txt
└── README.md
```

---

## 🔄 ML Pipeline Workflow

1. **Data Ingestion**

   * Load dataset from source
   * Split into train/test

2. **Data Transformation**

   * Handle categorical & numerical features
   * Apply encoding and scaling
   * Save preprocessor

3. **Model Training**

   * Train regression models
   * Evaluate performance
   * Save best model

4. **Prediction Pipeline**

   * Load model & preprocessor
   * Transform user input
   * Generate prediction

5. **Flask App**

   * User inputs data via UI
   * Model returns predicted score

---

## 🖥️ Running the Project Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/student-performance-predictor.git
cd student-performance-predictor
```

---

### 2️⃣ Create virtual environment

```
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Run the application

```
python app.py
```

---

### 5️⃣ Open in browser

```
http://127.0.0.1:5000/
```

---

## 📊 Sample Features Used

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

---

## 🎯 Key Highlights

✔ End-to-end ML pipeline
✔ Modular code structure
✔ Custom exception handling
✔ Reusable components
✔ Real-time prediction via Flask
✔ Deployment-ready architecture

---

## 🚀 Future Improvements

* Add model explainability (SHAP, LIME)
* Deploy on AWS Elastic Beanstalk
* Add user authentication
* Improve UI
* Integrate database for predictions

---




