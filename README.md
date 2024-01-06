# Bank Customer Churn Prediction
![Customer_Retention](customer-retenson.jpeg)

## Project Overview
This project involves predicting customer churn in the banking industry using machine learning techniques. It uses the Bank Customer Churn dataset to identify customers who are likely to leave the bank. The dataset includes various attributes such as customer ID, credit score, geography, gender, age, balance, and more.

## Dataset Description
The dataset, `Churn_Modelling.csv`, contains information about bank customers and their churn status. Key attributes include:

- **CustomerID**: Unique identifier for each customer.
- **Surname**: Customer's surname.
- **CreditScore**: Numerical value representing the customer's credit score.
- **Geography**: Customer's country (France, Spain, Germany).
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Tenure**: Number of years with the bank.
- **Balance**: Account balance.
- **NumOfProducts**: Number of bank products used.
- **HasCrCard**: Indicates if the customer has a credit card.
- **IsActiveMember**: Indicates if the customer is an active member.
- **EstimatedSalary**: Estimated salary of the customer.
- **Exited**: Indicates if the customer has churned.

## Libraries Used
- `pandas`
- `numpy`
- `sklearn` (for model building and preprocessing)
- `matplotlib`
- `seaborn`

## Steps in Analysis
1. **Data Loading and Preprocessing**
   - Importing data.
   - Handling missing values.
   - Dropping irrelevant columns.
   - One-hot encoding for categorical variables.
   - Feature scaling for numerical variables.

2. **Exploratory Data Analysis (EDA)**
   - Generating various plots to understand data distribution and relationships.

3. **Model Building**
   - Using `RandomForestClassifier` for predicting churn.
   - Training and testing the model.
   - Evaluating model performance using metrics like accuracy, confusion matrix, and classification report.

4. **Predictions and Submission**
   - Generating churn probabilities for test dataset.
   - Creating a submission file.

## Model Evaluation
The model's performance is evaluated based on accuracy, precision, recall, F1-score, and the confusion matrix.

## Usage
- Clone the repository.
- Run the Jupyter Notebook to train the model and make predictions.
- The dataset and trained model can be used to predict churn for new customer data.

## Contributions
Contributions to this project are welcome. You can suggest improvements or add new features.

## License
This project is licensed under the CC0: Public Domain.

