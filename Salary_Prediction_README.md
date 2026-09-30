# Salary Prediction Based on Work Experience - Machine Learning Web App

## Project Overview

This project is a Machine Learning web application that predicts an employee's salary based on work experience.

A Machine Learning regression model is trained using salary and work-experience data, saved as a model file, and integrated with a Flask web application. Users can enter their work experience through the web interface and receive a predicted salary.

## Objectives

- Analyze the salary and work-experience dataset.
- Prepare the data for Machine Learning.
- Train a regression model for salary prediction.
- Save the trained model for reuse.
- Integrate the model with Flask.
- Provide salary predictions through a web application.

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Preparation
   ↓
Regression Model Training
   ↓
Model Evaluation
   ↓
Save Trained Model
   ↓
Flask Web Application
   ↓
Salary Prediction
```

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Joblib
- HTML
- CSS

## Project Structure

```text
salary-prediction-ml/
│
├── app.py                 # Flask web application
├── salary_prediction.py   # Machine Learning/model code
├── model.pkl              # Saved trained model
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
├── .gitignore             # Git ignored files
│
├── templates/
│   ├── index.html         # Input page
│   └── result.html        # Prediction result page
│
└── static/
    └── css/
        ├── style.css      # Application styling
        └── stylenew.css   # Additional styling
```

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Move into the project directory:

```bash
cd salary-prediction-ml
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Flask application:

```bash
python app.py
```

Open the local URL shown in the terminal, usually:

```text
http://127.0.0.1:5000/
```

## Machine Learning Model

The project uses a regression-based Machine Learning approach to estimate salary from work experience.

The trained model is stored in:

```text
model.pkl
```

The Flask application loads the saved model and uses it to generate predictions from user input.

## Dataset

The dataset contains information related to work experience and corresponding salary values.

The model uses work experience as the input feature to learn the relationship between experience and salary.

## Web Application

The Flask application provides a simple interface where users can enter their work experience and receive a predicted salary.

The application separates:

- Flask backend logic
- HTML templates
- CSS styling
- Trained Machine Learning model

## Key Learning Outcomes

- Understanding regression-based Machine Learning.
- Data preprocessing and feature preparation.
- Model training and prediction.
- Saving and loading trained ML models.
- Integrating Machine Learning with Flask.
- Building a basic end-to-end ML web application.

## Future Improvements

- Compare multiple regression algorithms.
- Add model evaluation metrics such as MAE, MSE, RMSE and R².
- Add interactive data visualizations.
- Improve input validation and error handling.
- Improve the user interface.
- Deploy the application to a cloud platform.
- Add automated testing and CI/CD.

## Author

**Aayush Talaviya**

BCA | Data Science / Machine Learning

## Disclaimer

This project is created for educational and portfolio purposes. Salary predictions are estimates produced by a Machine Learning model and should not be treated as actual salary offers or professional compensation advice.
