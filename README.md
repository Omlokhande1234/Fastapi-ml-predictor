# 🧠 FastAPI ML Prediction System

A machine learning-powered backend application built with FastAPI to predict housing prices based on user-provided features. The system includes a trained `scikit-learn` model, RESTful APIs for inference, and PostgreSQL for logging predictions.

## 🚀 Features

- ✅ REST API endpoint (`/predict`) using **FastAPI**
- ✅ Trained **scikit-learn** regression model
- ✅ Input validation using **Pydantic**
- ✅ Logs predictions in **PostgreSQL** via **SQLAlchemy**
- ✅ Automatic API docs via **OpenAPI** (`/docs`)
- ✅ Fully **Dockerized** backend
- ✅ Ready to deploy on **Render**

## 🧱 Tech Stack

- **FastAPI** – Backend web framework
- **scikit-learn** – ML model training
- **Pandas** – Data preprocessing
- **SQLAlchemy** – ORM for PostgreSQL
- **PostgreSQL** – Relational DB to log predictions
- **Docker** – Containerized deployment
- **joblib** – Model serialization

## 📁 Project Structure

fastapi-ml-predictor/
├── app/
│ ├── main.py # API and routing
│ ├── model.py # ML training and joblib save
│ ├── schemas.py # Pydantic input model
│ ├── database.py # DB connection setup
│ ├── models.py # SQLAlchemy ORM model
├── model.pkl # Trained ML model
├── requirements.txt # Python dependencies
├── Dockerfile # For containerized deployment
├── README.md # Project documentation