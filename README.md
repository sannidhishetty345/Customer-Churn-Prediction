<img width="1854" height="968" alt="image" src="https://github.com/user-attachments/assets/20a2a2bc-a6a1-4273-944f-bedf8073a323" /># 🚀 Customer Churn Prediction API
### End-to-End Machine Learning Deployment using FastAPI, Docker & AWS Elastic Beanstalk

[![Live API](https://img.shields.io/badge/Live_API-Open-success?style=for-the-badge)](http://customerchurnprediction-env.eba-waz6pfsf.eu-north-1.elasticbeanstalk.com/)
[![FastAPI Docs](https://img.shields.io/badge/FastAPI-Swagger-009688?style=for-the-badge&logo=fastapi&logoColor=white)](http://customerchurnprediction-env.eba-waz6pfsf.eu-north-1.elasticbeanstalk.com/docs)
[![ReDoc](https://img.shields.io/badge/API-ReDoc-blue?style=for-the-badge)](http://customerchurnprediction-env.eba-waz6pfsf.eu-north-1.elasticbeanstalk.com/redoc)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/sannidhishetty345/Customer-Churn-Prediction)

---
---

## 📌 Project Overview

Customer churn is one of the most important business problems in the telecom industry. This project develops an end-to-end Machine Learning system capable of predicting whether a customer is likely to leave the company based on demographic information, account details, and service usage.

The project demonstrates the complete ML lifecycle—from data preprocessing and model training to API development, Docker containerization, cloud deployment, and version control.

---

## 🎯 Objectives

- Predict customer churn using Machine Learning
- Build a production-ready REST API using FastAPI
- Containerize the application with Docker
- Deploy the application on AWS Elastic Beanstalk
- Provide interactive API documentation using Swagger UI

---

## 🏗️ System Architecture

```
Customer
      │
      ▼
Swagger UI / REST API
      │
      ▼
FastAPI
      │
      ▼
Preprocessing Pipeline
      │
      ▼
Trained ML Model
      │
      ▼
Prediction
```

---

## ⚙️ Tech Stack

### Programming

- Python 3.11

### Machine Learning

- Scikit-Learn
- Pandas
- NumPy

### Backend

- FastAPI
- Uvicorn
- Pydantic

### Deployment

- Docker
- AWS Elastic Beanstalk
- Amazon EC2
- Amazon IAM

### Version Control

- Git
- GitHub

---

## 📂 Project Structure

```
Customer-Churn-Prediction
│
├── api/
├── artifacts/
├── config/
├── data/
├── src/
├── Dockerfile
├── requirements.txt
├── README.md
└── setup.py
```

---

## 📊 Machine Learning Pipeline

- Data Cleaning
- Feature Engineering
- Data Transformation
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization
- Prediction Pipeline

---

## 🌐 API Endpoints

### Home

```
GET /
```

Returns application status.

---

### Health Check

```
GET /health
```

Returns deployment health.

---

### Predict Customer Churn

```
POST /predict
```

Returns churn prediction for customer input.

---

## 📖 Swagger Documentation

Interactive API Documentation

```

```

---

## ☁️ Cloud Deployment

The application is successfully deployed using:

- Docker
- AWS Elastic Beanstalk
- Amazon EC2
- IAM Roles
- Public REST API

---

## 🚀 Running Locally

Clone repository

```bash
git clone https://github.com/sannidhishetty345/Customer-Churn-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run application

```bash
uvicorn api.app:app --reload
```

Visit

```
http://localhost:8000/docs
```

---

## 📈 Future Improvements

- CI/CD using GitHub Actions
- Model Monitoring
- MLflow Remote Tracking
- Frontend using Streamlit
- AWS S3 Model Versioning
- Authentication
- Kubernetes Deployment

---

## 👩‍💻 Author

**Sannidhi Shetty**

Computer Science Engineering (Data Science)

GitHub:
https://github.com/sannidhishetty345

---

## ⭐ If you found this project useful, please consider giving it a star.
