# 💊 Medicine Recommendation System

A machine learning-based web application that predicts diseases based on user-input symptoms and recommends appropriate medicines, precautions, and descriptions. Built using **Flask**, this project demonstrates the integration of ML models with a web interface.

---

## 🚀 Features

* 🧠 **Disease Prediction**

  * Predicts disease based on symptoms entered by the user
  * Uses trained machine learning models

* 💊 **Medicine Recommendation**

  * Suggests medicines based on predicted disease

* 📋 **Precautions & Description**

  * Displays precautionary measures
  * Provides disease-related information

* 🌐 **Web Interface**

  * Interactive UI built with Flask and HTML/CSS
  * Easy-to-use symptom input form

---

## 🧠 Machine Learning

* **Models Used:**

  * Decision Tree
  * Random Forest
  * Naive Bayes

* **Processes:**

  * Data preprocessing
  * Feature encoding
  * Model training
  * Prediction

* **Evaluation Metrics:**

  * Accuracy
  * Classification Report

---

## 🖥️ Tech Stack

### 🔹 Backend

* Flask
* Python

### 🔹 Frontend

* HTML
* CSS
* Bootstrap (optional)

### 🔹 Libraries

* pandas
* numpy
* scikit-learn
* pickle

---

## 📁 Project Structure

```
MedicineRecommendationSystem-WellnessHub/
│
├── main.py                 # Flask app (main backend)
├── wsgi.py                 # WSGI configuration
├── test_app.py             # Application tests
├── requirements.txt        # Python dependencies
├── Procfile                # Heroku deployment configuration
│
├── templates/              # HTML files
│   ├── index.html          # Home page with symptom input
│   ├── about.html          # About page
│   ├── contact.html        # Contact page
│   ├── developer.html      # Developer info page
│   └── blog.html           # Blog page
│
├── static/                 # Static assets
│   └── img.png             # Images
│
├── Datasets/               # Training and reference data
│   ├── Training.csv        # Model training data
│   ├── symtoms_df.csv      # Symptoms dataset
│   ├── medications.csv     # Medications dataset
│   ├── precautions_df.csv  # Precautions dataset
│   ├── description.csv     # Disease descriptions
│   ├── diets.csv           # Diet recommendations
│   ├── workout_df.csv      # Workout recommendations
│   └── Symptom-severity.csv# Symptom severity data
│
├── models/                 # Trained ML model
│   ├── svc.pkl             # Support Vector Classifier model
│   └── MedicineRecommendationSystem.ipynb  # Model training notebook
│
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

---

## 🔄 Application Flow

```
User Inputs Symptoms
        ↓
Flask Receives Request
        ↓
ML Model Predicts Disease
        ↓
Display Results:
   - Disease Name
   - Recommended Medicines
   - Precautions
   - Description
```

---

## 🌐 Routes

* `/` → Home Page (Symptom Input Form)
* `/predict` → Handles prediction and displays results

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ADINA-ISRAN/MedicineRecommendationSystem-WellnessHub.git
cd MedicineRecommendationSystem-WellnessHub-main
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application

```bash
python main.py
```

---

## 🌍 Run the App

Open your browser and go to:

```
http://127.0.0.1:5000/
```

---

## ⚠️ Disclaimer

This project is intended for **educational purposes only**.
The recommendations provided should not be considered medical advice. Always consult a healthcare professional.

---

## 📈 Future Enhancements

* 🤖 Use advanced ML/DL models
* 📱 Improve UI/UX responsiveness
* 🔐 Add user authentication
* 🌐 Deploy on cloud platforms
* 📊 Add health analytics dashboard

---

## 🎯 Purpose

This project demonstrates:

* Application of machine learning in healthcare
* Flask-based web development
* Integration of ML models with web interfaces
* Solving real-world problems using data

---

## 👨‍💻 Author

* ADINA ISRAN

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
