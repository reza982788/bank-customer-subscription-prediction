# Bank Marketing Campaign Analysis

This repository contains the analysis of bank marketing campaign data to predict customer subscription to term deposits using machine learning algorithms.

## Project Overview

This project analyzes the Bank Marketing dataset from UCI Machine Learning Repository to predict whether a customer will subscribe to a term deposit. The analysis includes data preprocessing, exploratory data analysis, feature engineering, and implementation of various machine learning models.

## Dataset

The dataset used in this analysis is the "Bank Marketing" dataset from UCI Machine Learning Repository:
- Source: https://archive.ics.uci.edu/dataset/222/bank+marketing
- File used: bank-full.csv
- Contains 17 columns (16 features + 1 target variable)
- 45,211 records

### Features
- age: Age of the customer
- job: Type of job (categorical)
- marital: Marital status
- education: Education level
- default: Has credit in default?
- balance: Average yearly balance
- housing: Has housing loan?
- loan: Has personal loan?
- contact: Contact communication type
- day: Last contact day of the week
- month: Last contact month of year
- duration: Last contact duration (seconds)
- campaign: Number of contacts performed
- pdays: Days since last contact
- previous: Number of previous contacts
- poutcome: Outcome of previous campaign

### Target Variable
- y: Has the client subscribed a term deposit? (yes/no)

## Repository Structure

- `bank_marketing_analysis.ipynb`: Main analysis notebook containing the complete data analysis and machine learning implementation
- `bank_marketing_overview.ipynb`: Documentation notebook explaining the dataset, features, and problem domain
- `bank-full.csv`: The dataset file (not included in repository, must be downloaded separately)
- `requirements.txt`: Python package dependencies
- `README.md`: This file

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Requirements

To run the notebooks, you need the following Python packages (specified in requirements.txt):
- pandas==2.1.0
- numpy==1.24.3
- matplotlib==3.7.2
- seaborn==0.12.2
- scikit-learn==1.3.0
- imbalanced-learn==0.10.1
- jupyter==1.0.0
- notebook==6.5.5

## Usage

1. Download the dataset from the UCI Machine Learning Repository
2. Place the `bank-full.csv` file in the same directory as the notebooks
3. Open and run the notebooks in Jupyter Notebook or JupyterLab:
   - Start with `bank_marketing_overview.ipynb` to understand the dataset and problem
   - Then run `bank_marketing_analysis.ipynb` for the complete analysis

## Analysis Steps

The analysis includes:
1. Data Preprocessing
   - Handling missing values
   - Feature encoding
   - Data normalization

2. Exploratory Data Analysis
   - Statistical analysis
   - Feature distributions
   - Correlation analysis
   - Data visualization

3. Feature Engineering
   - Feature selection
   - Handling class imbalance using SMOTE
   - Data splitting for training and testing

4. Model Implementation
   - Logistic Regression
   - Decision Tree
   - Gradient Boosting
   - Neural Network

5. Model Evaluation
   - Performance metrics
   - Confusion matrices
   - ROC curves
   - Model comparison

## Results

The analysis provides insights into:
- Key factors affecting term deposit subscription
- Model performance comparison
- Feature importance analysis
- Recommendations for bank marketing strategies

## License

This project is for academic purposes and uses data from the UCI Machine Learning Repository. The code is available under the MIT License. 