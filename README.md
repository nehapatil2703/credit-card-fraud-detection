## Credit Card Fraud Detection

This repository contains a Jupyter Notebook for detecting credit card fraud using machine learning techniques. The dataset and models are utilized to identify fraudulent transactions in financial systems, aiming to enhance fraud prevention mechanisms.

#### Features

- Data Preprocessing: Handles class imbalance, scales features, and prepares data for model training.

- Exploratory Data Analysis (EDA): Insights into transaction patterns, correlations, and fraud trends.

- Machine Learning Models: Includes implementation and evaluation of algorithms such as Logistic Regression and Random Forest.

- Evaluation Metrics: Assesses model performance using accuracy, precision, recall, F1 score, and confusion matrices.

#### Getting Started

##### Prerequisites

Ensure you have Python 3.8 or later and the following libraries installed:

- pandas

- numpy

- matplotlib

- seaborn

- scikit-learn

- imbalanced-learn

Install dependencies with:

pip install -r requirements.txt

#### Dataset

The dataset used for this project is a public credit card transaction dataset, which contains anonymized transaction features. Fraudulent transactions are marked as 1 in the target column, and legitimate transactions are marked as 0.

#### Running the Notebook

- Clone this repository:

git clone https://github.com/yourusername/credit-card-fraud-detection.git

- Navigate to the project directory:

cd credit-card-fraud-detection

- Open the Jupyter Notebook:

jupyter notebook creditcard_fraud.ipynb

- Run the cells sequentially to preprocess the data, train models, and evaluate results.

#### Results

The best-performing model achieved a high precision and recall for fraudulent transactions.

Evaluation metrics are visualized for better interpretability.

#### Acknowledgments

The dataset was sourced from Kaggle's Credit Card Fraud Detection.
