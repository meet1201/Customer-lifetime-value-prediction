# Customer Lifetime Value Prediction

## Overview
This project develops a predictive model to estimate the Customer Lifetime Value (CLV) for customers of a telecom company. CLV is a critical metric that helps businesses understand a customer's worth over time to tailor marketing efforts and maximize profit.

## Data Description
The dataset includes historical customer transaction data such as `TotalSpending`, `NumberOfTransactions`, and the calculated `CLV`. The data was sourced from the company's internal CRM system.

## Features
- `TotalSpending`: Total money spent by the customer.
- `NumberOfTransactions`: Total number of transactions made by the customer.
- `AverageSpending`: Average amount spent per transaction.
- `IsHighValue`: Indicates whether the customer's spending is in the top 25% of all customers.

## Models Used
- **Random Forest Regressor**: Chosen for its ability to handle non-linear data and provide feature importance.

## File Descriptions
- `CLV.ipynb`: Jupyter notebook containing the analysis, model building, and evaluation.

## How to Run
1. Ensure Python 3 and Jupyter Notebook are installed.
2. Install dependencies: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.
3. Run the notebook: `jupyter notebook CLV.ipynb`.

## Results
The RandomForest model achieved an R² score of 0.90, suggesting good predictive performance.

## Dashboard
A Power BI dashboard is created to visualize the results and insights from the model dynamically. It includes visualizations of customer segments, predicted CLV, and feature importances.

## Future Work
- Integrate more detailed customer demographic data.
- Explore advanced machine learning models for improved accuracy.
- Deploy the model as a web application for real-time predictions.

## Authors
- [Meet Patel]

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
