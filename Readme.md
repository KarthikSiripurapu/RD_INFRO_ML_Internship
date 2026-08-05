# Customer Churn Prediction

## Overview

This project predicts whether a telecom customer is likely to churn using supervised machine learning techniques. It covers the complete ML workflow from data collection and preprocessing to model training, evaluation, and inference using a lightweight Flask API.

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Model Serialization using Pickle
- Flask API for model inference

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Flask
- Joblib

---

## Dataset

Telco Customer Churn Dataset

Target Variable:

- Churn (Yes/No)

---

## Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Save Trained Model
8. Flask Prediction API

---

## Project Structure

```text
data/
models/
notebooks/
app.py
README.md
requirements.txt
```

---

## Results

- Accuracy: ~80%
- Successfully classified customers likely to churn.
- Saved trained model for future inference.

---

## API

### GET /

Returns API status.

### POST /predict

Accepts customer details in JSON format and returns the predicted churn class.

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Model Deployment on Render/Heroku
- Docker Support

