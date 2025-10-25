# Student Productivity Prediction System

A **machine learning-powered dashboard** that predicts student productivity based on daily activity patterns.  
The system analyzes factors like sleep duration, study hours, screen time, physical activity, and caffeine intake to provide **personalized productivity insights and recommendations** for students.

---

## 🎯 Project Purpose

This project is designed for:

- **Students**: Optimize daily routines for better academic performance.
- **Educators**: Gain data-driven insights about factors affecting student productivity.
- **Researchers**: Study the relationship between lifestyle habits and academic performance.
- **Health Professionals**: Understand the impact of sleep and activity on cognitive function.

---

## ✨ Key Features

- **AI-Powered Predictions**: Uses a Random Forest Regressor model trained on real student data.
- **Interactive Dashboard**: Modern, responsive interface with dark/light mode toggle.
- **Personalized Recommendations**: Suggestions based on user input patterns.
- **Visual Analytics**: Multiple charts showing feature impact, comparisons, and trends.
- **Productivity Scoring**: Generates a 0–100 productivity score with confidence levels.
- **History Tracking**: Records and visualizes prediction trends over time.
- **Export Functionality**: Download detailed productivity reports in text format.

---

## 🛠 Technology Stack

### Backend
- Python 3.8+
- Flask (API development)
- Scikit-learn (ML implementation)
- Pandas & NumPy (data manipulation)
- Joblib (model serialization)

### Frontend
- HTML5, CSS3, JavaScript (ES6+)
- Chart.js (data visualization)
- Font Awesome (icons)

### Data Science / ML
- Random Forest Regressor (primary prediction algorithm)
- Feature Engineering: normalization and scaling
- Model Evaluation: R² scoring and performance metrics

---

## 📁 Project Structure
AI-Productivity-Dashboard/
├── app.py # Flask API server
├── main.py # Model training script
├── student_sleep_patterns.csv # Dataset
├── random_forest_model.pkl # Trained ML model
├── model_metadata.json # Feature importance & metadata
├── features_list.pkl # List of model features
├── index.html # Web interface
├── style.css # Stylesheet
├── script.js # Frontend logic
├── linear_regression_model.pkl # Backup model
├── linear_regression_scaler.pkl # Scaler for backup model
└── README.md # Project documentation


---

## 🚀 Setup Instructions

### Prerequisites
- Python 3.8+  
- pip package manager  
- Modern browser (Chrome, Firefox, Edge, Safari)  

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/Ritik5629/AI-Productivity-Dashboard.git
cd AI-Productivity-Dashboard
```
2. Create a virtual environment
```bash
python -m venv venv
```
