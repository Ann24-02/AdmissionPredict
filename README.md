# Lab 2: Polynomial Regression & Linear Regression

## Description
This notebook demonstrates experiments with linear and polynomial regression. We work with both synthetic data and a real dataset `Admission_Predict.csv`.

- Polynomial regression of different degrees (1, 4, 15)  
- Data scaling using MinMaxScaler  
- Train-test split of the dataset  
- Training LinearRegression model and evaluating performance with MAE, MSE, and RMSE  

## Dataset: Admission_Predict.csv
The dataset contains information about graduate school applicants. Key features include:

- `GRE Score` — Applicant's GRE score  
- `TOEFL Score` — Applicant's TOEFL score  
- `University Rating` — Rating of the target university  
- `SOP` — Strength of Statement of Purpose  
- `LOR` — Strength of Letter of Recommendation  
- `CGPA` — Undergraduate GPA  
- `Research` — Research experience (0 or 1)  
- `Chance of Admit` — Target variable, probability of admission (0 to 1)

## Installation
Make sure you have the required Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
