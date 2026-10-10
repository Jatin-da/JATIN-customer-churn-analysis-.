# Enterprise Customer Churn Prediction & Advanced Artificial Intelligence Analytics

## Project overview
This project demonstrates customer churn prediction using Python and a Logistic Regression machine-learning model.

## Dataset
The script generates 1,200 synthetic customer records for demonstration. It does not use real customer data.

## Features used
- Age
- Tenure in months
- Monthly charges
- Support calls
- Contract type
- Internet service
- Payment method

## Model and workflow
1. Generate synthetic sample data.
2. Split the data into training and test sets.
3. Preprocess numeric and categorical features.
4. Train a Logistic Regression model.
5. Print accuracy, ROC-AUC, and a classification report.
6. Save metrics and a confusion-matrix plot in the `outputs/` folder.

## Requirements
Install the libraries listed in `requirements.txt`:
```bash
pip install -r requirements.txt
```

## Run the project
```bash
python customer_churn_prediction.py
```

## Important limitation
The dataset is synthetic, and results are for educational demonstration only. They should not be presented as real-world customer churn performance.
