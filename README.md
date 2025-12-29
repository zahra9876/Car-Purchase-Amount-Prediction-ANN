# Car Purchase Amount Prediction using Artificial Neural Networks (ANN) 🚗💸

This project implements a Deep Learning model to predict the maximum amount a customer is willing to spend on a car. It uses customer demographic and financial data to provide accurate price predictions.

## 📌 Project Overview
The goal of this project is to develop a regression model using **Artificial Neural Networks (ANN)**. By analyzing customer data such as annual salary and net worth, the model can estimate the "Car Purchase Amount" for potential buyers, helping car dealerships optimize their sales strategies.

## 📊 Dataset Information
The model is trained on the `Car_Purchasing_Data.csv` dataset, which includes:
- **Customer Name & Email** (Pre-processing: Dropped)
- **Country** (Pre-processing: Dropped/Encoded)
- **Gender** (Binary)
- **Age**
- **Annual Salary**
- **Credit Card Debt**
- **Net Worth**
- **Car Purchase Amount** (Target Variable)

## 🛠️ Installation & Requirements
To run this project, you need to install the following Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
