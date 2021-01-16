# Churn-Reduction

# Objective
Make a logistic regression model to predict churn of customers

# Predictor Variables
1. account length 
2. international plan  
3. voicemail plan  
4. number of voicemail messages  
5. total day minutes used  
6. day calls made  
7. total day charge  
8. total evening minutes  
9. total evening calls  
10. total evening charge  
11. total night minutes  
12. total night calls  
13. total night charge  
14. total international minutes used  
15. total international calls made 
16. total international charge
17. number of customer service calls made 
18. State (location)

# Target Variable
1. move: if the customer has moved (1=yes; 0 = no) 

# Libraries used 
pandas , numpy, seaborn, 

# AUROC values of models
1. Logistic Regression : 0.695
2. Random Forest after hyperparameter tuning : 0.894
3. XGBoost after hyperparameter tuning : 0.866
