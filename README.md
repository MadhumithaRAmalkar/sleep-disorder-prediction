# Sleep Disorder Prediction

This project is a machine learning application for predicting sleep disorders based on health and lifestyle data. It uses a Flask web application to provide an interface for users to input their data and receive predictions.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Files and Directories](#files-and-directories)
- [Acknowledgements](#acknowledgements)

## Project Structure

Sleep_Disorder_Prediction/
│
├── app.py
├── best_model.pkl
├── BMI Category_encoder.pkl
├── Gender_encoder.pkl
├── Occupation_encoder.pkl
├── scaler.pkl
├── Sleep Disorder_encoder.pkl
├── Sleep_health_and_lifestyle_dataset.csv
├── main_old.py
├── Model_new.py
├── predict.py
├── predict_new.py
├── static/
│ └── [static files]
├── templates/
│ └── [HTML templates]
└── .idea/
└── pycache/
└── catboost_info/








## Installation

1. **Clone the repository:**

```bash
git clone <repository_url>
cd Sleep_Disorder_Prediction/Sleep
2. Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. Install the required packages:
pip install -r requirements.txt
Usage
Run the Flask application:
python app.py
Open your web browser and go to:
http://127.0.0.1:5000
Use the interface to input your health and lifestyle data to get a prediction of sleep disorders.
Files and Directories
app.py: Main script to run the Flask web application.
best_model.pkl: Trained machine learning model for prediction.
BMI Category_encoder.pkl, Gender_encoder.pkl, Occupation_encoder.pkl, Sleep Disorder_encoder.pkl: Encoders for categorical variables.
scaler.pkl: Scaler used for feature scaling.
Sleep_health_and_lifestyle_dataset.csv: Dataset used for training and testing.
main_old.py, Model_new.py, predict.py, predict_new.py: Additional scripts for model training and prediction.
static/: Directory for static files (CSS, JavaScript).
templates/: Directory for HTML templates.
Acknowledgements
This project uses a dataset from Kaggle and various Python libraries including Flask, scikit-learn, and XGBoost.
