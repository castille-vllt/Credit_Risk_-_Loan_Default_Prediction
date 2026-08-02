# Credit_Risk_and_Loan_Default_Prediction
## Summary

This project develops a machine learning approach to **assess credit risk and predict loan defaults** based on borrower and loan characteristics.

### Key Components

* **Exploratory Data Analysis (EDA):** analyzes relationships between borrower characteristics, FICO scores, interest rates, debt-to-income ratios, and loan outcomes.
* **Data Preprocessing:** prepares numerical and categorical variables for machine learning.
* **Model Comparison:** trains and compares Ridge and Lasso Logistic Regression, Random Forest, and Decision Tree models.
* **Model Evaluation:** assesses model performance using Accuracy, Precision, Recall, F1-score, AUC, MSE, ROC curves, confusion matrices, and 5-fold cross-validation.
* **Feature Importance:** identifies the variables that have the greatest impact on loan default prediction.
* **Hyperparameter Tuning:** optimizes the Decision Tree model using GridSearchCV.
* **Risk Grading:** converts predicted default probabilities into **A–G risk grades** to facilitate risk interpretation.

### Banking Application

This model could be applied by banks as a **credit risk assessment tool** during the loan approval process. Based on a borrower's predicted probability of default, the system could support:

* **Automated approval** of low-risk applications
* **Manual review** of medium-risk applications
* **Rejection or additional safeguards** for high-risk applications

This approach could help banks **standardize lending decisions, improve risk assessment, reduce potential credit losses, and make the loan approval process more efficient**, while keeping final decisions under appropriate human and regulatory oversight.
