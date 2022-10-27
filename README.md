# Car-Evaluation

In this project, I build classification models to predict the evaluaion of the car based on their characteristics. This dataset has 1728 records, each represents a car evaluation. Each car evaluation is described with 7 attributes. 6 of the attributes represent car characteristics, such as buying price, price of the maintenance, number of doors, capacity in terms of persons to carry, the size of luggage boot, and estimated safety of the car. The seventh variable represents the evaluation of the car (unacceptable, acceptable, good, very good).    

First, I applied Nested Grid Search CV technique to find the best cross validation scores of 5 models among decision tree, logistic regression, KNN, Naive Bayes, and SVM. 'Decision Tree': 0.95 'Logistic Regression': 0.90 'KNN': 0.83 'Naive Bayes': 0.80 'SVM': 0.99 SVM model performs the best among all 5 models.
Therefore, I used SVM method and trained another model to get the best hyperparameter. Based on the confusion matrix, the final accuracy is 97%.


To get more information about the dataset: https://archive.ics.uci.edu/ml/datasets/car+evaluation
