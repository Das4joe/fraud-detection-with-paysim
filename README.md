# fraud-detection-with-paysim
Machine learning project to detect financial fraud using the PaySim synthetic dataset.
# Fraud Detection with PaySim

This project demonstrates the use of machine learning to detect fraudulent transactions using the PaySim synthetic dataset.

## Project Features
- Data Exploration: Understand the dataset with visualizations and statistical summaries.
- Feature Engineering: Transform raw data into features suitable for machine learning.
- Fraud Detection Model: Train a logistic regression model to identify fraudulent transactions.
- Evaluation: Analyze model performance with metrics like Precision, Recall, and AUC-ROC.

## Dataset
The dataset simulates mobile money transactions and includes features such as:
- `type`: Type of transaction (e.g., CASH-IN, TRANSFER).
- `amount`: Transaction amount.
- `isFraud`: Label indicating whether the transaction is fraudulent.

**Source**: [PaySim Dataset on Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)

## Project Structure
fraud-detection-with-paysim/ │ ├── data/ # Placeholder for dataset files ├── notebooks/ # Jupyter Notebooks │ ├── data_exploration.ipynb # Data exploration │ ├── feature_engineering.ipynb # Feature engineering │ └── fraud_detection_baseline.ipynb # Model training and evaluation ├── scripts/ # Python scripts │ ├── data_preprocessing.py │ ├── model_training.py │ └── model_evaluation.py ├── requirements.txt # Python dependencies ├── LICENSE # Project license └── README.md # Project overview
