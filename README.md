# Laptop Price Prediction

This project is a machine learning regression project that predicts laptop prices based on hardware specifications and product features.

The main focus of the project was handling a messy real-world dataset with inconsistent values, noisy text fields, and many unique specifications. A large part of the work involved cleaning and engineering features before training the regression model.

---

## Overview

Laptop prices depend on many technical factors such as processor, GPU, RAM, storage type, screen specifications, and brand. However, real-world laptop datasets often store these specifications in inconsistent text formats.

This project focuses on preparing these features properly and using them to build a price prediction model.

---

## Main Work

The project included:

- Cleaning inconsistent laptop specification fields
- Extracting useful information from GPU names
- Identifying GPU manufacturer and model category
- Processing RAM values
- Separating SSD and HDD storage information
- Handling noisy and high-cardinality categorical features
- Encoding categorical variables
- Training and evaluating regression models

---

## Dataset

The dataset included laptop specifications such as:

- Brand
- Processor
- GPU
- RAM
- Storage
- Screen specifications
- Price

The full dataset may not be included directly in this repository depending on file size and sharing limitations.

---

## Model Performance

The project achieved strong predictive performance after extensive preprocessing and feature engineering.

> Note: Since this is a regression task, the final result should be reported using regression metrics such as R² score, MAE, or RMSE rather than classification accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Machine Learning
- Regression
- Feature Engineering

---

## Repository Structure

```text
laptop-price-prediction/
├── data/        # Dataset notes or sample data
├── notebooks/   # Main project notebook
├── .gitignore
└── README.md
