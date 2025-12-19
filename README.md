*Diabetes Prediction Model*

Project Overview

The Diabetes Prediction Model is a machine learning–based system designed to predict whether an individual is diabetic or non-diabetic based on clinical and physiological parameters. The project leverages a Random Forest Classifier for accurate prediction and integrates a web-based frontend for real-time user interaction.

The system includes exploratory data analysis (EDA), data cleaning, visualization, and model optimization to ensure reliable predictions. It provides a decision-support tool for preliminary diabetes risk assessment and awareness.

Key Features

Predicts diabetes based on key health indicators:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

Body Mass Index (BMI)

Diabetes Pedigree Function (DPF)

Age

Comprehensive EDA with histograms and heatmaps

Data cleaning and preprocessing for improved model accuracy

Random Forest Classifier with hyperparameter optimization

Accuracy comparison and feature importance visualization

Web-based frontend using Flask, HTML, and CSS

Real-time prediction output with user-friendly interface

Tech Stack

Programming Language: Python

Data Handling: Pandas, NumPy

Machine Learning: Scikit-learn

Visualization: Matplotlib, Seaborn

Web Framework: Flask

Frontend: HTML, CSS

Installation

Clone the repository:

git clone https://github.com/your-username/diabetes-prediction-model.git
cd diabetes-prediction-model


Create and activate a virtual environment (optional but recommended):

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


Install required packages:

pip install -r requirements.txt


Place your trained model (model.pkl) in the project directory.

Usage

Run the Flask application:

python app.py


Open your web browser and go to:

http://127.0.0.1:5000/


Input health parameters in the form and click Predict.

View prediction result on the result page (Diabetic / Non-Diabetic).

Project Structure
diabetes-prediction-model/
│
├── app.py                # Flask application
├── model.pkl             # Trained Random Forest model
├── templates/
│   ├── index.html        # Input page
│   └── result.html       # Prediction result page
├── static/
│   └── style.css         # CSS styling
├── diabetes.csv          # Dataset
└── README.md             # Project documentation

Screenshots

Input Page:


Prediction Result:


References

Kaggle: Diabetes Dataset

WHO: Diabetes Information

CDC: Diabetes Basics

Scikit-learn Documentation: https://scikit-learn.org

Flask Documentation: https://flask.palletsprojects.com

Future Scope

Integration with larger and diverse datasets for improved generalization

Inclusion of additional clinical and lifestyle parameters

Exploration of deep learning and ensemble techniques for enhanced accuracy

Implementation of explainable AI (XAI) methods for interpretability

Deployment on cloud platforms for scalability and multi-user access

Development of mobile application interface and interactive dashboards

Author

Anshuman Hota
Email: your.email@example.com
