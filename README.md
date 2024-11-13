# Credit-Card-Default-Risk-Prediction

## Project Overview
This project uses machine learning to predict the likelihood of credit card defaults using the "Default of Credit Card Clients" dataset. It covers data preprocessing, feature engineering, model development, and evaluation, with an emphasis on classification techniques like logistic regression.

## Dataset
The dataset used in this project, "Default of Credit Card Clients," contains financial and demographic information of credit card clients, which includes features such as:
- `LIMIT_BAL` (Credit Limit)
- `SEX` (Gender)
- `AGE` (Age)
- `BILL_AMT_*` (Bill Amount for the past months)
- `PAY_AMT_*` (Payment Amount for the past months)
- And other features related to credit and payment history.

The dataset is available in this repository and is ready to be used for the analysis.

## Steps Involved
1. **Data Preprocessing**  
   - Handling missing values
   - Encoding categorical features
   - Scaling/normalizing numerical features

2. **Model Building**  
   - Logistic Regression and other classification algorithms
   - Hyperparameter tuning

3. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC curve

## Requirements
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib, Seaborn

## Installation

Clone the repository:
```bash
git clone https://github.com/way2aravind/Credit-Card-Default-Risk-Prediction.git
