# Data Directory

This folder contains the datasets used for the **Customer Account Dormancy Prediction** project.

The data represents anonymized banking activity records and was processed specifically for analytical and modeling purposes.

---

## Dataset Description

The primary dataset used in this project includes customer-level transactional and behavioral information required to identify potential dormancy patterns.

Key characteristics of the dataset include:

- Customer demographic attributes
- Account information such as balance and tenure
- Transaction frequency and activity history
- Derived behavioral indicators used for predictive modeling

All features were prepared to ensure they reflect only historical information available prior to the prediction window, thereby preventing any form of data leakage.

---

## File Structure

### `customer_dormancy_dataset.csv`

This file contains the cleaned and processed data used for model training and evaluation.

It includes:

- Demographic features (age, gender, city)
- Account characteristics (type, balance, age of account)
- Transaction activity measures
- Time-aware behavioral features
- Dormancy target variable for supervised learning

---

## Data Processing Notes

Before being used for modeling, the dataset underwent several preprocessing steps:

- Removal of identifiers not relevant to prediction
- Standardization of date formats
- Handling of missing values using conservative imputation strategies
- Feature engineering based strictly on historical transaction records

No synthetic data generation or resampling techniques were applied during preparation.

---

## Usage Guidelines

This dataset is intended exclusively for academic and demonstration purposes.

It should not be considered representative of any real banking institution, and all records have been anonymized.

---
