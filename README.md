# Online-Payment-Fraud-Detection

# Project Overview

This project aims to detect fraudulent online payment transactions using machine learning techniques. It leverages historical transaction data to identify patterns indicative of fraud, helping financial institutions mitigate risks and protect users from fraudulent activities.


# Features

- Data Preprocessing:  Cleansing and transforming raw transaction data.

- Exploratory Data Analysis (EDA): Identifying fraud patterns using statistical and visualization techniques.

- Feature Engineering: Creating meaningful features for better fraud detection.

- Model Training: Implementing machine learning algorithms for classification.

- Evaluation & Optimization: Assessing model performance and tuning hyperparameters.

- Deployment: Deploying the fraud detection model via API or a dashboard.

# Technologies Used

- Python (pandas, numpy, scikit-learn, imbalanced-learn, Flask/FastAPI for deployment)

- Jupyter Notebook for data exploration and model training

- Power BI/Tableau for visualization (optional)

- MySQL/PostgreSQL for storing transaction data

# Installation

- Clone the repository:

- git clone https://github.com/your-repo/online-fraud-detection.git
cd online-fraud-detection

- Create and activate a virtual environment:

- python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


- Install dependencies:

- pip install -r requirements.txt

# Dataset

- The dataset used contains transaction details such as amount, location, timestamp, payment method, and fraud labels.

- If using a public dataset, it can be obtained from Kaggle or other sources.

#  Model Training

1.Load and preprocess the dataset.

2.Perform exploratory data analysis.

3.Apply feature selection and engineering.

4.Train models (Logistic Regression, Decision Tree, Random Forest, XGBoost, etc.).

5.Evaluate performance using metrics such as precision, recall, F1-score, and AUC-ROC.

6.Deploy the best-performing model.

# Usage

Run the model training script:

python train_model.py

To deploy the model using Flask:

python app.py

API endpoint for prediction:  POST /predict
{
  "transaction_details": {
    "amount": 500.00,
    "location": "New York",
    "payment_method": "Credit Card"
  }
}






