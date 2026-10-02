# Brain_Stroke_Prediction
# Brain Stroke Prediction

A machine learning web application that predicts the likelihood of stroke based on patient health and demographic information.

## Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas
- Joblib
- HTML/CSS

## Features

- User-friendly web interface for entering patient information
- Pre-trained machine learning model for stroke prediction
- Flask-based web application
- Prediction results displayed through a dedicated result page

## Input Features

The application uses factors such as:

- Gender
- Age
- Hypertension
- Heart Disease
- Ever Married
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status

## Project Structure

```text
Brain-Stroke-Prediction/
├── app.py
├── model.joblib
├── requirements.txt
├── train.csv
├── test.csv
├── Stroke Prediction Using Python.ipynb
└── templates/
    ├── index.html
    └── result.html
