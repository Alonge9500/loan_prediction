# Loan Prediction Analysis
By *Alonge Daniel*, a Data Scientist passionate about data and technology.

- GitHub: [Alonge 9500](https://github.com/Alonge9500)
- LinkedIn: [Alonge Daniel](https://www.linkedin.com/in/alonge-daniel-27b4b4139/)
- Email: [Alonge Daniel](mailto:alongedaniel19@gmail.com)
- Streamlit App [App ](https://alonge9500-loan-prediction-app-fgk31d.streamlit.app/)

I' will appreciate any comment and correction on this work 
This repository contains code for a loan prediction analysis project. The aim of this project is to use machine learning techniques to predict the likelihood of loan approval based on various factors.

## Problem Statement

The traditional process of making decisions on bank loans using credit scores, application forms, and credit reference agencies can be cumbersome, error-prone, and biased. The aim of this research work is to propose a machine learning model that can identify irregularities during the application of online loans, such as the unawareness of the guarantor regarding the loan until it is time for repayment. The goal is to use machine learning to determine who is eligible for loans and establish the criteria needed to qualify for a loan easily.

## Data Description

The project uses a dataset containing information about loan applicants. The dataset includes the following columns:

- Loan_ID: Unique identifier for each loan applicant
- Gender: Gender of the loan applicant
- Married: Marital status of the loan applicant
- Dependents: Number of dependents the loan applicant has
- Education: Education level of the loan applicant
- Self_Employed: Whether the loan applicant is self-employed or not
- ApplicantIncome: Income of the loan applicant
- CoapplicantIncome: Income of the co-applicant (if any)
- LoanAmount: Amount of the loan requested
- Loan_Amount_Term: Term of the loan in months
- Credit_History: Credit history of the loan applicant
- Property_Area: Area where the property is located
- Loan_Status: Status of the loan application (approved or not)

## Getting Started

To run the code in this repository, follow these steps:

1. Clone the repository: `git clone <repository_url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Download the dataset files (train.csv and test.csv) and place them in the project directory.
4. Run the Jupyter notebook: `jupyter notebook`
5. Open the notebook `loan_prediction_analysis.ipynb` and execute the code cells sequentially.

## Exploratory Analysis

The notebook includes exploratory analysis of the loan dataset. It visualizes the distribution of loan amounts, examines the relationship between loan amount and loan status, and explores the correlation between credit history and loan approval.

## Data Preprocessing

The notebook performs data preprocessing tasks, such as handling missing values and encoding categorical variables. Missing values are imputed using appropriate methods, and categorical variables are encoded using label encoding and one-hot encoding techniques.

## Machine Learning Model

The notebook builds a machine learning model to predict loan approval. It uses various algorithms such as logistic regression, random forest, and XGBoost. The model is trained on the training dataset and evaluated using appropriate evaluation metrics.

## Conclusion

The loan prediction analysis project aims to provide insights into loan approval decisions using machine learning techniques. By analyzing the dataset and building a predictive model, it helps in understanding the factors that influence loan approval and enables better decision-making in the lending process.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the code and adapt it to your requirements.
