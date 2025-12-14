# CreditPath - Smart Loan Predictor

## Overview


**CreditPath - Smart Loan Predictor** is a machine learning project aimed at predicting loan approval based on various applicant features. The application leverages a variety of machine learning algorithms to analyze historical loan data and provide predictive insights for new loan applications.
![image](https://github.com/user-attachments/assets/65969728-bf32-45c2-8114-da500841deff)

![image](https://github.com/user-attachments/assets/a4452339-c6bb-432b-8438-bc71692857b8)
![image](https://github.com/user-attachments/assets/93da8ee5-81e8-4952-9584-44b6367470c4)

## Features

- **Data Preprocessing:** Cleans and transforms input data for model training.
- **Model Training:** Utilizes different algorithms to train models on historical loan data.
- **Prediction:** Provides loan approval predictions based on applicant information.
- **Interactive Form:** User-friendly web interface for inputting applicant data.

## Project Structure

```
CreditPath/
│
├── dataset/
│   ├── train_data.csv       # Training dataset
│   └── test_data.csv        # Testing dataset
│
├── Loan_Prediction_Project.ipynb  # Jupyter Notebook for model development and analysis
│
├── app/
│   ├── static/              # Static files such as CSS and JavaScript
│   ├── templates/          # HTML templates for the web interface
│   └── app.py              # Flask application file
│
└── README.md               # This file
```


## Usage

1. **Upload Data:**

   Place your dataset CSV files in the `dataset/` folder.

2. **Access the Web Interface:**
https://loan-predictor-dibo.onrender.com
   You will be able to input applicant details and get loan approval predictions.   

![image](https://github.com/user-attachments/assets/93da8ee5-81e8-4952-9584-44b6367470c4)


4. **Model Training and Testing:**

   Open the Jupyter Notebook `Loan_Prediction_Project.ipynb` to see the model training, evaluation, and testing process.

## Dependencies

- Flask
- scikit-learn
- pandas
- numpy
- xgboost
- seaborn
- matplotlib
- (Other dependencies listed in `requirements.txt`)


