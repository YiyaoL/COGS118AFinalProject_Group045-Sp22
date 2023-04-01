# COGS118A Supvr/Mach Learning Algorithms Final Project

This repo contains the code& data for the final project for COGS118A in Spring 2022.

In this project, we built prediction models that predict whether or not someone has heart disease based on their health status and ethnographic data. We cleaned the 2020 CDC survey data of 400k adults and choose the features including Smoking, Stroke, PhysicalHealth, DiffWalking, AgeCategory,Diabetic, PhysicalActivity, GenHealth, and KidneyDisease. We split the data into training and testing set, and used gridsearch with four algorithms (Logistic Regression, KNN, Decision Tree, Random Forest) to find four sets of best hyperparameters. We compared the results on the test set, using accuracy and recall as evaluation metrics, and used a 10-fold cross validation to further select the best model, adding roc_auc_score and mean squared error as our metric. Among the four, we decided that best_logistic is the best model. It generates around 73.45% accuracy and has a roc for about 75.3% with the smallest standard deviation across folds.

The final results are summarized in: [final Report](https://github.com/YiyaoL/COGS118AFinalProject_Group045-Sp22/blob/main/FinalProject_group045.ipynb).
