# Calorie-Burnt-Prediction
## Description
This project aims to predict the number of calories burned during various physical activities using machine learning. The model considers user-specific attributes such as age, weight, height, gender, and activity levels to provide precise calorie burn predictions. The implementation leverages **Flask**, **Python**, and **XGBoost** to develop an interactive and efficient calorie prediction system.

By offering personalized insights, this project helps individuals optimize their fitness routines and improve health management. The web-based interface built with Flask allows users to input their details and receive real-time calorie burn predictions.

## Features
- Machine learning-based calorie prediction using XGBoost
- User-friendly web interface built with Flask
- Data preprocessing and feature engineering for accurate predictions
- Integration of real-world dataset with age, weight, height, gender, and activity details
- Continuous learning approach to improve accuracy over time
- API endpoints to support seamless integration with other fitness platforms

## Technologies Used
- Python(Pandas, NumPy, XGBoost, Flask)
- Machine Learning(Regression models, XGBoost algorithm)
- Flask (Backend framework for web interface and API)
- HTML/CSS(Frontend UI)
- Jupyter Notebook (Model training and evaluation)

## Installation
To run this project locally, follow these steps:

### 1. Clone the repository
```bash
   cd "C:\Users\Sai Vinny Reddy\Desktop\Calorie Burnt Prediction\Metabometer-main"
```

### 2. Install dependencies
```bash
   pip install flask
pip install xgboost
```

### 3. Run the Flask App
```bash
   python app.py
```

### 4. Access the Web App
Open your browser and go to:
```bash
   http://127.0.0.1:5000/
```

## Dataset
The dataset used in this project consists of multiple attributes, including:
- Age
- Weight (kg)
- Height (cm)
- Gender
- Activity Type (e.g., running, cycling, walking)
- Duration (minutes)
- Heart Rate (bpm)
- Calories Burned

Data preprocessing steps include handling missing values, feature scaling, and encoding categorical variables.

## Model Training
- **Data Preprocessing**: Cleaning, normalization, and feature selection
- **Algorithm Used**: XGBoost (Extreme Gradient Boosting)
- Evaluation Metrics: Mean Squared Error (MSE), R-Squared (R²)
- Hyperparameter Tuning: GridSearchCV for optimal performance


## Future Enhancements
- Deploying on cloud platforms like AWS/GCP
- Expanding dataset for better accuracy
- Mobile app integration for real-time tracking


