# -ML-Prediction-API-Deployment-FastAPI-Docker-AWS-EC2-
# Insurance Premium Prediction API

A FastAPI-based machine learning API that predicts a user's insurance premium category based on age, BMI, income, smoking status, city, and occupation.

## Features

- Predicts insurance premium category using a trained ML model
- FastAPI backend with automatic Swagger documentation
- Pydantic validation for user input
- Health check endpoint for model status
- Docker support for easy deployment

## Tech Stack

- Python
- FastAPI
- Pydantic
- Pandas
- Scikit-learn
- Uvicorn
- Docker

## Project Structure

```text
insurance-premium-prediction-fastapi/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── config/
│   └── city_tier.py
├── model/
│   ├── model.pkl
│   └── predict.py
└── schema/
    ├── user_input.py
    └── prediction_response.py
