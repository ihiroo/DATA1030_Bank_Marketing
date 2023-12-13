# Binary Classification in Bank Marketing
Objective: to develop a predictive model capable of accurately assessing the likelihood of clients subscribing to a term deposit

Preprocessors: StandardScaler(), OneHotEncoder(), OrdinalEncoder()

Splitting (use stratification):

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For anti-XGBoost: cross-validation using 10 folds (80%), test set (20%)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For XGBoost: 6:2:2 (train_test_split)

Candidate models: Logistic Regression, Lasso, Ridge, Elastic Net, Random Forest, XGBoost

Evaluation metric: F1 Score

Best performance: Random Forest with a mean F1 of 0.546 (baseline: 0.2025)

Required library versions:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python version 3.11.4

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numpy version 1.24.4

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;matplotlib version 3.7.2
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sklearn version 1.3.0
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pandas version 2.0.3
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;xgboost version 1.7.6

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;shap version 0.42.1

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;seaborn version 0.12.2
