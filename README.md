# Loan Approval Prediction Application

[![Python Version](https://img.shields.io/badge/python-3.x-blue)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-2.2.5-green)](https://flask.palletsprojects.com/)

This repository contains a Flask-based web application for predicting loan approval status. It uses a trained machine learning model to estimate loan approval outcomes based on user-provided data.

---

## Features

- User-friendly web interface for loan approval predictions.
- API endpoint to accept JSON input for predictions.
- Utilizes a pre-trained machine learning model pipeline (`loan_approval_pipeline.pkl`).
- Predicts loan approval status with an accuracy of **96.7%**.

---

## Input Parameters

- **Number of Dependents**: Number of dependents the applicant has.
- **Education**: Applicant's education level (e.g., Graduate, Not Graduate).
- **Self Employed**: Whether the applicant is self-employed (Yes/No).
- **Income Per Annum**: Applicant's annual income.
- **Loan Amount**: Loan amount applied for.
- **Loan Term**: Loan term in months.
- **CIBIL Score**: Applicant's credit score.
- **Residential Assets Value**: Value of residential properties owned.
- **Commercial Assets Value**: Value of commercial properties owned.
- **Luxury Assets Value**: Value of luxury assets owned.
- **Bank Asset Value**: Total value of bank assets.

---

## Installation and Setup

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/manitejagaddam/loan-approval-predictor.git
   cd loan-approval-predictor
   ```
2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the Application**
   ```bash
   python app.py
   ```

## Model Accuracy
- The machine learning model used in this application achieves an accuracy of 96.7%, making it highly reliable for loan approval predictions.
- Model Used is Decision Tree with max_depth as 7
