Customer Churn Prediction Using Artificial Neural Networks
Overview

This project involves predicting customer churn using an Artificial Neural Network (ANN). The goal is to analyze customer data and predict whether a customer will leave a company based on their attributes and usage patterns.
Dataset

The dataset includes various features related to customer demographics, service usage, and billing information. The columns in the dataset include:

    gender: Gender of the customer (1 for Female, 0 for Male)
    SeniorCitizen: Senior citizen status (1 for Yes, 0 for No)
    Partner: Whether the customer has a partner (1 for Yes, 0 for No)
    Dependents: Whether the customer has dependents (1 for Yes, 0 for No)
    tenure: Number of months the customer has been with the company
    PhoneService: Whether the customer has phone service (1 for Yes, 0 for No)
    MultipleLines: Whether the customer has multiple lines (1 for Yes, 0 for No)
    OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Various service features (1 for Yes, 0 for No)
    PaperlessBilling: Whether the customer uses paperless billing (1 for Yes, 0 for No)
    MonthlyCharges: Monthly charges incurred by the customer
    TotalCharges: Total charges incurred by the customer
    Churn: Whether the customer has churned (1 for Yes, 0 for No)

Project Components

    Data Preprocessing:
        Clean and preprocess the data to handle missing values and categorical features.
        Apply one-hot encoding for categorical variables.
        Scale numeric features.

    Model Building:
        Construct and train an Artificial Neural Network (ANN) using TensorFlow/Keras.
        Define the architecture of the neural network and compile the model.

    Model Evaluation:
        Evaluate the model's performance using accuracy, precision, recall, and F1-score.
        Test the model with custom inputs to make predictions.

    Deployment:
        Prepare the model for deployment and use it to predict churn for new customers.

Getting Started

    Clone the Repository:

    bash

git clone https://github.com/your-username/customer-churn-prediction.git

Install Dependencies:

bash

    pip install -r requirements.txt

    Run the Jupyter Notebook:
        Open customer_churn_prediction.ipynb and execute the cells to see the analysis and results.

    Custom Input:
        Use the predict function in the provided script to input custom customer data and get churn predictions.

Files Included

    customer_churn_prediction.ipynb: Jupyter notebook with the entire analysis and model building process.
    data/: Directory containing the dataset used for training and testing.
