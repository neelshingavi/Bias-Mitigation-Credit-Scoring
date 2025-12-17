# ⚖️ Bias-Mitigation Credit Scoring

[![Python](https://img.shields.io/badge/python-3.8+-blue?logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-1.1.2-orange?logo=flask)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A backend application for **credit scoring** with **bias mitigation**.  
Predicts credit approval while detecting and mitigating biases in decision-making based on sensitive attributes like **gender, race, or age**.

---

## 🌟 Features

- Predict credit approval using pre-trained machine learning models.
- Evaluate fairness metrics such as demographic parity and equal opportunity.
- Provides API endpoints for predictions and fairness analysis.
- Easily extensible for custom datasets and models.

---

## 🗂️ Project Structure

```

Bias-Mitigation-Credit-Scoring/
├── backend/
│   ├── app.py            # Flask API backend
│   ├── models/           # Pre-trained models
│   ├── utils/            # Preprocessing & fairness functions
│   └── requirements.txt  # Python dependencies
├── data/                 # Sample datasets
├── frontend/             # Optional frontend interface
└── README.md

````

---

## 🚀 API Usage

### **POST `/predict`**
Send JSON with user features to get a credit prediction.  

```json
{
  "age": 30,
  "income": 50000,
  "gender": "male",
  "loan_amount": 20000
}
````

### **GET `/fairness-metrics`**

Returns fairness evaluation metrics of the model, such as:

* Demographic parity
* Equal opportunity
* Disparate impact analysis

---

## 📊 Bias & Fairness

This project includes **methods to evaluate and mitigate bias** in credit scoring, ensuring fairer predictions across different sensitive groups.

---

## 💻 Technology Stack

* Python 3.8+
* Flask
* Pandas
* Scikit-learn
* Joblib / Pickle

---

## 📬 Contact

For questions or contributions, reach out to **shingavineel@gmail.com**.
