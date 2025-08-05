# 🏦 Customer Churn Prediction Web Application

This project is a machine learning-powered web application that predicts whether a customer will churn (i.e., leave the bank). Using customer data such as age, balance, and geography, the application provides real-time churn prediction through a simple web interface.

## 📌 Key Features
- Predicts if a customer will leave the bank using pre-trained ML model.
- User-friendly web interface for entering customer data.
- Model trained and serialized using Scikit-learn.
- Built with Flask for lightweight and fast deployment.

## 📂 Project Structure
'''
Customer-Churn-Prediction/
├── templates/
│ └── index.html                     # Web interface template for input and prediction
│
├── app.py                           # Flask application file
├── Customer Churn Prediction.ipynb  # Jupyter notebook for model training

## 🛠 Technologies Used
- **Python 3**
- **Flask** – For web interface and routing
- **Scikit-learn** – For training the classification model
- **Pickle** – For model serialization
- **HTML/CSS** – For frontend UI (assumed in `templates/` folder)

## 🧠 Model Details
- Model Type: **Random Forest Classifier**
- Input Features:
  - Credit Score
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Has Credit Card (0 or 1)
  - Is Active Member (0 or 1)
  - Estimated Salary
  - Geography (France, Spain, Germany) – One-hot encoded
  - Gender (Male/Female) – Binary encoded
- Output:
  - **1** → Customer will leave the bank
  - **0** → Customer will not leave the bank
