# Insurance-premium-prediction

An end-to-end **Machine Learning powered Insurance Premium Category Prediction system** built using **FastAPI** for backend APIs and **Streamlit** for an interactive frontend.  
The system predicts the **insurance premium category (Low / Medium / High)** based on user demographic and lifestyle details.

---

## 🚀 Project Overview

This project demonstrates how a trained Machine Learning model can be deployed as a **production-ready REST API** and consumed by a frontend application.

### 🔹 Key Features
- FastAPI-based backend for high-performance API handling
- Streamlit-based frontend for user-friendly interaction
- ML model integration for real-time predictions
- Input validation using Pydantic
- Scalable and modular project structure
- Docker-ready architecture 

---

## 🧠 Machine Learning Logic

The model predicts insurance premium category using the following derived and raw features:

- BMI (Body Mass Index)
- Age Group (young, adult, middle-aged, senior)
- Lifestyle Risk (low, medium, high)
- City Tier (Tier 1 / 2 / 3)
- Annual Income (LPA)
- Occupation

Feature engineering is handled dynamically using **computed fields** inside the FastAPI backend.

---

## 🏗️ Tech Stack

| Layer | Technology |
|------|-----------|
| Programming Language | Python |
| Backend API | FastAPI |
| Frontend UI | Streamlit |
| ML Libraries | Scikit-learn, Pandas |
| Model Serialization | Pickle |
| API Client | Requests |
| Validation | Pydantic |
| Deployment | Uvicorn |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```bash
insurance-premium-prediction/
│
├── app.py # FastAPI backend
├── frontend.py # Streamlit frontend
├── model/
│ └── model.pkl # Trained ML model
├── config/ # Configuration files
├── schema/ # Input/output schemas
├── requirements.txt # Dependencies
├── Dockerfile # Containerization
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/Sejal-07/Insurance-premium-prediction.git
cd Insurance-premium-prediction
```
### Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
---







