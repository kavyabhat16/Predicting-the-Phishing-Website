# Predicting-the-Phishing-Website
The objective is to identify whether a website is a Phishing website one or not.This code written in python(using jupyter notebbok).

Algorithm used and Accuracy Results:
#1) Logistic regression(0.93)
#2)Decision tree classifier(0.91)
#3)XG Boost classifier(0.94)
#4)Random Forest classifier algorithm(0.97)
So,By using the RandomForestClassifier,we got the best optimised model with a score of 0.97. so it can be used as a model to detect whether the webiste is phishy or not. 


Steps typically involved in this project:

1)Feature Extraction: Extracted file of format .CSV

2)Exploratory Data Analysis(Including Data visualization): such as finding missing values,removing unnecessary variables and filtering the extracted features data.

3)Training the model:
  Since it is a classification problem I have used diffrent classifier algorithm to predict the phishing website:
  Training the model with the above mentioned algorithms
  Calculating the accuracy of the model by evaluating the performance of the model, choosing the best fit for this problem.Here Random       Forest is the best fit

4)Evaluating the model and Testing the model:
 Used Area under the curve and confusion matrix in order find which model is a good fit and how accurately model is predicting the values.
