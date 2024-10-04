# Customer Churn Analysis

## Overview
This project analyzes customer churn in the telecommunications industry using a dataset containing over 7,000 customer records. The goal is to identify key factors influencing churn, enabling businesses to develop effective retention strategies. By examining customer demographics, service subscriptions, and payment methods, this analysis provides valuable insights into customer behavior.

## Dataset
The dataset used for this analysis contains the following key features:
- **CustomerID**: Unique identifier for each customer
- **gender**: Gender of the customer
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1: Yes, 0: No)
- **Partner**: Indicates if the customer has a partner (Yes/No)
- **Dependents**: Indicates if the customer has dependents (Yes/No)
- **tenure**: Number of months the customer has been with the company
- **PhoneService**: Indicates if the customer has phone service (Yes/No)
- **MultipleLines**: Indicates if the customer has multiple lines (Yes/No)
- **InternetService**: Type of internet service (DSL, Fiber optic, No)
- **OnlineSecurity**: Indicates if the customer has online security (Yes/No)
- **Churn**: Indicates if the customer has churned (Yes/No)
- **Contract**: Type of contract (Month-to-month, One year, Two year)
- **PaperlessBilling**: Indicates if the customer has paperless billing (Yes/No)
- **PaymentMethod**: Customer's payment method
- **MonthlyCharges**: Monthly charges for the customer
- **TotalCharges**: Total charges for the customer

## Key Insights
1. **Churn Rate**: Approximately **26.6%** of customers have churned.
2. **Contract Type**: Month-to-month contracts have higher churn rates compared to longer contracts.
3. **Payment Method**: Customers using electronic checks show higher churn rates.
4. **Demographics**: Senior citizens and customers without dependents tend to churn more frequently.
5. **Internet Service**: Fiber optic users exhibit the highest churn rates.

## Technologies Used
- **Python**: For data analysis and visualization
- **Pandas**: For data manipulation
- **Matplotlib/Seaborn**: For data visualization
- **Jupyter Notebook**: For conducting and documenting the analysis

## How to Use
1. Clone the repository to your local machine.
2. Install the required libraries (if not already installed):
   ```bash
   pip install pandas matplotlib seaborn
   
