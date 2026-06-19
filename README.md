# Kredent AI - Financial Risk Intelligence Platform

> **Analyze. Predict. Prosper.**

Kredent AI is an AI-powered Financial Risk Intelligence Platform that helps users understand their financial health, assess credit risk, evaluate loan affordability, and make smarter financial decisions using Machine Learning and Explainable AI.

---

## Overview

Financial decisions are often made without a clear understanding of risk, affordability, and long-term impact. Kredent AI bridges this gap by leveraging Machine Learning to provide personalized financial insights and risk assessments.

The platform empowers users to:

* Understand their financial health
* Evaluate loan affordability
* Assess repayment risk
* Receive personalized financial recommendations
* Improve financial planning and decision-making

---

# Problem Statement

Millions of individuals apply for loans or make financial commitments without understanding:

* Their financial risk profile
* Debt management capabilities
* Loan affordability limits
* Long-term financial consequences

Traditional systems focus on approval or rejection.

Kredent AI focuses on empowering users with actionable financial intelligence before they make critical financial decisions.

---

# Key Features

## Financial Health Score

Generates a Financial Health Score (0–100) based on:

* Annual Income
* Credit Amount
* Existing Liabilities
* Employment Status
* Family Status
* Housing Conditions
* Financial Stability Indicators

Example:

```text
Financial Health Score: 82/100
```

---

## Credit Risk Prediction

Predicts the probability of financial repayment difficulties.

Output:

```text
Risk Level: Low Risk

Default Probability: 12%
```

---

## Loan Affordability Analysis

Determines whether a user can safely afford a requested loan.

Example:

```text
Requested Loan: ₹10,00,000

Recommended Loan: ₹8,50,000

Status: Moderate Risk
```

---

## Personalized Financial Recommendations

Provides AI-driven recommendations such as:

* Debt reduction strategies
* Savings optimization
* Emergency fund planning
* Responsible borrowing guidance
* Financial habit improvements

---

## Explainable AI

Uses SHAP Explainability to provide transparency behind every prediction.

Example:

```text
Risk Increased Due To:

• High debt-to-income ratio
• Large credit amount
• Low annual income
```

---

## Customer Segmentation

Categorizes users into financial profiles:

* Financially Stable
* Growth Potential
* Moderate Risk
* High Risk

This enables personalized financial planning.

---

# Machine Learning Pipeline

## Dataset

**Home Credit Default Risk Dataset**

The dataset contains real-world customer financial information used to predict repayment difficulties.

Features include:

* Income Information
* Credit Amount
* Family Status
* Employment Information
* Housing Information
* Credit History Indicators

---

## Data Preprocessing

* Missing Value Handling
* Feature Engineering
* Outlier Detection
* Encoding Categorical Features
* Data Normalization
* Feature Selection

---

## Model Development

Algorithms:

* Logistic Regression
* Random Forest
* XGBoost

Future Models:

* LightGBM
* CatBoost

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

# System Architecture

```text
User Input
    │
    ▼
Frontend Dashboard
    │
    ▼
FastAPI Backend
    │
    ▼
Machine Learning Engine
    │
    ▼
Risk Assessment Module
    │
    ▼
Recommendation Engine
    │
    ▼
Financial Insights Dashboard
```

---

# Tech Stack

## Frontend

* Next.js
* TypeScript
* Tailwind CSS
* Chart.js

## Backend

* FastAPI
* Python

## Machine Learning

* Scikit-Learn
* XGBoost
* Pandas
* NumPy

## Explainable AI

* SHAP

## Database

* PostgreSQL

## Deployment

### Frontend

* Vercel

### Backend

* Render

### Database

* PostgreSQL

---

# Project Structure

```bash
kredent-ai/

├── data/
│   └── application_train.csv
│
├── notebooks/
│   ├── eda.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│   └── model_evaluation.ipynb
│
├── models/
│   ├── xgboost_model.pkl
│   ├── scaler.pkl
│   └── encoder.pkl
│
├── backend/
│   ├── app.py
│   ├── routes/
│   ├── services/
│   ├── schemas/
│   └── utils/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── pages/
│   └── public/
│
├── docs/
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/ndheeraj-shetty/kredent-ai.git

cd kredent-ai
```

---

## Create Virtual Environment

```bash
python -m venv venv

source venv/bin/activate

# Windows
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Backend

```bash
uvicorn app:app --reload
```

---

## Run Frontend

```bash
npm install

npm run dev
```

---

# Sample Output

```text
Financial Health Score: 82/100

Risk Level: Low Risk

Default Probability: 12%

Recommended Loan Amount: ₹8,50,000

Recommendations:

• Maintain emergency savings
• Reduce unnecessary debt
• Keep debt-to-income ratio below 35%
```

---

# Roadmap

## Version 1

* Financial Health Score
* Risk Prediction
* Loan Affordability Analysis
* Personalized Recommendations

## Version 2

* Customer Segmentation
* Interactive Financial Dashboard
* Advanced Analytics

## Version 3

* AI Financial Assistant

## Version 4

* RAG-Based Financial Advisor
* Financial Knowledge Base

## Version 5

* Multi-Agent Financial Planning System
* Voice-Based Financial Assistant
* Investment Insights
* Retirement Planning

---

# Expected Impact

Kredent AI aims to:

* Improve financial literacy
* Reduce risky borrowing decisions
* Encourage responsible debt management
* Increase transparency in financial planning
* Empower users through AI-driven financial intelligence

---

# Skills Demonstrated

This project showcases expertise in:

* Machine Learning
* Credit Risk Modeling
* Feature Engineering
* Explainable AI
* Financial Analytics
* FastAPI
* Next.js
* Full-Stack Development
* Model Deployment
* MLOps Fundamentals

---

# Author

**Nagasuri Satya Dheeraj**

Artificial Intelligence & Machine Learning Engineer

Interests:

* Machine Learning
* Deep Learning
* NLP
* LLMs
* RAG Systems
* Financial AI

---

# Support

If you find this project useful, consider giving it a star on GitHub.

---

## Kredent AI

### Analyze. Predict. Prosper.
