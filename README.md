# Electric-Vehicle-Purchase-DataSet
End-to-end EV purchase prediction using EDA, feature engineering, model comparison, XGBoost tuning, and 3-fold stratified cross-validation. The final XGBoost model achieved ~0.9416 mean ROC-AUC and was trained on the full dataset for final predictions.
This notebook presents an end-to-end machine learning approach for predicting whether a customer is likely to purchase an Electric Vehicle (EV).

The workflow includes data exploration, target analysis, feature engineering, model comparison, hyperparameter tuning, stratified cross-validation, and final prediction generation.

I experimented with Logistic Regression, Decision Tree, Random Forest, and XGBoost, with XGBoost achieving the best performance.

The final model uses carefully selected interaction features involving subsidy availability, home charging capability, and range anxiety. Multiple additional feature-engineering approaches were tested and removed when they did not improve cross-validation performance.

The final XGBoost model achieved approximately 0.9416 mean ROC-AUC using 3-fold stratified cross-validation, with stable performance across folds.

The final model was trained on the complete training dataset and used to generate probability predictions for the test dataset in the required Kaggle submission format.

Key techniques: EDA, feature engineering, categorical encoding, XGBoost, hyperparameter tuning, stratified cross-validation, ROC-AUC optimization.
