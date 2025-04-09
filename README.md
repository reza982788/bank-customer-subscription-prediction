# Bank Customer Subscription Prediction

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on their demographic and financial information. The project uses machine learning techniques to analyze customer data and build predictive models.

## Project Overview

The project aims to help Banco de Portugal optimize its marketing campaigns for term deposit subscriptions by predicting customer behavior. The analysis is conducted using machine learning algorithms to identify patterns and factors that influence customer decisions regarding term deposits.

## Dataset

The dataset used in this project is the "Bank Marketing" dataset from the UCI Machine Learning Repository. It contains information about direct marketing campaigns of a Portuguese banking institution.

### Features

The dataset includes the following features:
- **Demographic Information:**
  - Age
  - Job type
  - Marital status
  - Education level

- **Financial Information:**
  - Credit default status
  - Average yearly balance
  - Housing loan status
  - Personal loan status

- **Campaign Information:**
  - Contact communication type
  - Last contact day and month
  - Contact duration
  - Number of contacts during campaign
  - Days since last contact
  - Previous campaign contacts
  - Previous campaign outcome

### Target Variable
- **y**: Whether the client subscribed to a term deposit (binary: 'yes' or 'no')

## Project Structure

The project consists of two main Jupyter notebooks:

1. `term_deposits_prediction_overview.ipynb`: Contains the initial data exploration and preprocessing steps
2. `term_deposits_prediction_analysis.ipynb`: Contains the detailed analysis and model implementation

## Implementation Details

### Data Preprocessing
- Handling missing values and data cleaning
- Encoding categorical variables using LabelEncoder
- Feature scaling and normalization
- Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

### Machine Learning Models
The project implements and compares multiple machine learning models:
1. Logistic Regression
2. Decision Tree Classifier
3. Gradient Boosting Classifier
4. Neural Network (MLP Classifier)

### Model Evaluation
- Classification metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Confusion Matrix analysis
- ROC-AUC curves
- Feature importance analysis

### Key Findings
- Analysis of factors influencing term deposit subscription
- Identification of most important features
- Model performance comparison
- Business insights and recommendations

## Requirements

The project requires the following Python packages:
- pandas==2.1.0
- numpy==1.24.3
- matplotlib==3.7.2
- seaborn==0.12.2
- scikit-learn==1.3.0
- imbalanced-learn==0.10.1
- jupyter==1.0.0
- notebook==6.5.5

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Usage

1. Open `term_deposits_prediction_overview.ipynb` to understand the dataset and initial analysis
2. Open `term_deposits_prediction_analysis.ipynb` to explore the detailed analysis and model implementation

## Results

The project includes:
- Exploratory data analysis
- Feature engineering
- Model training and evaluation
- Performance metrics and insights
- Business recommendations based on model findings

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a new branch
3. Making your changes
4. Submitting a pull request

## License

This project is open-source and available under the MIT License. 