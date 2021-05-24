
## Card Transaction Fraud Detection:
  - DQR.ipynb: start the project with a data quality report to understand the data better and have a good sense to create variables;
  - Data Preprocessing.ipynb: Clean the data field by field and apply Geocoding a lot for address;
  - variables.ipynb: build more than 490 new candidate variables;
  - Distance Since Last Seen Variable.ipynb: one special variable reflect the distance between transactions;
  - Feature Selection.ipynb: use univariate filter (using KS score and FDR at 3% score) and backward wrapper methods to achieve a list of variables ranked by importance;
  - Build Model.ipynb: build different models such as Logistic Regression, Random Forest, Gradient Boosting and other models with tuning different parameters to find the best model;
  - model performance table.xlsx: summary of model performance;  
  - final_report.xlsx: Final report after reruning the final chosen model with training set, testing set and out of time set showing the performance with increment of data records;
