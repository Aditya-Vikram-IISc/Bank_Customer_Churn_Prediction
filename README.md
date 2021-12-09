# Bank_Customer_Churn_Prediction
Customer churn refers to the phenomenon when a customer leaves a company or an organisation. The ML model aims to predict the customers going to churn basis their data to that timely intervention can be introduced by the bank to retain them

# Summary of the process
1. We compared across a wide range of Classifiers namely Logistic Regression, SVM w/ different Kernel, Random Forest and XGBoost
2. Feature Engineering was performed to obtain new features from existing features which were initially not capable of differentiating between the two classes individually
3. Grid Search was performed with 10CV (in somecase we limited to 3CV due to RAM constraints) and the best parameter was selected for each of the model
4. All algorithms with their best weighst were fitted and XGBoost emerged as the clear winner in terms of PR
5. Futher, to push up the performance of XGBoost we further introduced SMOTE for undersampling of the minority class
6. XGBoost model trained on this dataset has the optimum results for the given case

Refer notebook for more info
