# House Price Prediction using SVR

This project predicts California house prices using
Support Vector Regressor (SVR) and Machine Learning.

---

# Dataset

Dataset used:
California Housing Prices Dataset

Download from Kaggle:
https://www.kaggle.com/datasets/camnugent/california-housing-prices

After downloading:
- Extract the ZIP file
- Place `housing.csv` inside the project folder

---

# Project Structure

house_price_project/
│
├── housing.csv
├── app.py
├── requirements.txt
└── README.md

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SVR (Support Vector Regressor)

---

# Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Handle Missing Values
4. Feature Selection
5. Feature Scaling
6. Train-Test Split
7. Train SVR Model
8. Evaluate Model
9. Predict House Prices

---

# Features Used

- median_income
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households

Target:
- median_house_value

---

# Installation

Install required libraries:

pip install -r requirements.txt

---

# Run the Project

Run the Python file:

python app.py

---

# Model Used

Support Vector Regressor (SVR)

Kernel used:
- RBF Kernel

---

# Evaluation Metrics

- Mean Absolute Error (MAE)
- R2 Score

---

# Sample Output

Mean Absolute Error: 84500.23

R2 Score: 0.71

Predicted House Price: 245000.45

---

