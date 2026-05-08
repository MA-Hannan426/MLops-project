# 📈 Sales Forecasting MLOps Project

An end-to-end **Sales Forecasting MLOps Pipeline** built using Machine Learning and DevOps practices to automate data processing, model training, evaluation, deployment, and monitoring.

---

# 🚀 Project Overview

This project predicts future sales using historical sales data and applies modern **MLOps practices** for scalable and reproducible machine learning workflows.

The pipeline includes:

- Data Ingestion
- Data Cleaning & Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- Experiment Tracking
- CI/CD Automation
- Model Deployment
- Monitoring & Retraining

---

# 🧠 Problem Statement

Businesses often struggle to predict future sales accurately. Poor forecasting can lead to:

- Overstocking
- Understocking
- Revenue loss
- Supply chain issues

This project uses Machine Learning models to forecast sales trends and automate the ML lifecycle using MLOps tools.

---

## Tech Stack
- Programming & ML
- Python
- Scikit-learn
- Pandas
- NumPy
- XGBoost
- Visualization
- Matplotlib
- Seaborn
- Plotly

## MLOps Tools
- MLflow
- DVC
- Docker
- GitHub Actions
- Fast API
- Kubernetes
- Airflow
- Promethius
- Grafana

---

# 🏗️ Project Architecture

```text
               ┌─────────────────┐
               │   Raw Dataset   │
               └────────┬────────┘
                        │
                        ▼
              ┌──────────────────┐
              │ Data Processing  │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Feature Engineering │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Model Training   │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Model Evaluation │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Model Registry   │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Deployment API   │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Monitoring       │
              └──────────────────┘
