# Telco-Customer-Churn-Prediction

This project focuses on predicting customer churn for a telecommunications company using machine learning algorithms. The goal is to build a model that can predict whether a customer will leave the service (churn) based on various customer attributes such as their service usage, demographic information, and subscription details.

## Dataset

The dataset contains the following columns:
- **customerID**: Unique identifier for each customer
- **gender**: Gender of the customer
- **SeniorCitizen**: Whether the customer is a senior citizen (1 = Yes, 0 = No)
- **Partner**: Whether the customer has a partner (Yes/No)
- **Dependents**: Whether the customer has dependents (Yes/No)
- **tenure**: Number of months the customer has been with the company
- **PhoneService**: Whether the customer has phone service (Yes/No)
- **MultipleLines**: Whether the customer has multiple lines (Yes/No)
- **InternetService**: Type of internet service the customer has (DSL/Fiber optic/No internet service)
- **OnlineSecurity**: Whether the customer has online security (Yes/No/No internet service)
- **OnlineBackup**: Whether the customer has online backup (Yes/No/No internet service)
- **DeviceProtection**: Whether the customer has device protection (Yes/No/No internet service)
- **TechSupport**: Whether the customer has tech support (Yes/No/No internet service)
- **StreamingTV**: Whether the customer has streaming TV service (Yes/No/No internet service)
- **StreamingMovies**: Whether the customer has streaming movies service (Yes/No/No internet service)
- **Contract**: Type of contract the customer has (Month-to-month, One year, Two year)
- **PaperlessBilling**: Whether the customer has paperless billing (Yes/No)
- **PaymentMethod**: Method of payment (Electronic check, Mailed check, Bank transfer, Credit card)
- **MonthlyCharges**: Monthly charges for the customer
- **TotalCharges**: Total charges incurred by the customer
- **Churn**: Whether the customer churned (Yes/No)

## Objective

The objective of this project is to predict whether a customer will churn or not based on their service and demographic features. The machine learning models used include:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Approach

1. **Data Preprocessing**:
   - Cleaned the data by handling missing values, encoding categorical variables, and scaling numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the relationships between different features and the target variable (Churn).
   - Checked for any imbalances in the dataset and handled them.

3. **Model Training**:
   - Split the data into training and testing sets.
   - Trained multiple machine learning models on the dataset and evaluated them using accuracy, precision, recall, F1-score, and confusion matrices.

4. **Evaluation**:
   - Evaluated the models using metrics like accuracy and classification report.

## Results

| Model             | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.8176   | 0.6824    | 0.5818 | 0.6281   |
| Decision Tree      | 0.7225   | 0.4770    | 0.5013 | 0.4889   |
| Random Forest      | 0.7963   | 0.6581    | 0.4799 | 0.5550   |
| XGBoost            | 0.7821   | 0.6078    | 0.4987 | 0.5479   |

## Conclusion

- Logistic Regression outperformed the other models with an accuracy of 81.76% and the highest F1 score of 0.6281.
- Random Forest showed a reasonable accuracy of 79.63%, but with lower precision and recall for the churn class.
- XGBoost performed slightly worse than Random Forest, with an accuracy of 78.21%.
- Decision Tree had the lowest performance across all metrics.

## Technologies Used

- **Python**: The programming language used for implementing the models.
- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` and `seaborn` for data visualization
  - `sklearn` for machine learning algorithms and metrics
  - `xgboost` for the XGBoost model

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sumbal-ilyass/sumbal-ilyass-Telco-Customer-Churn-Prediction./tree/main

