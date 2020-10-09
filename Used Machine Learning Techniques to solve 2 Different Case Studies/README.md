
## Problem 1:

You are hired by one of the leading news channel CNBE who wants to analyze recent elections. This survey was conducted on 1525 voters with 9 variables. You have to build a model, to predict which party a voter will vote for on the basis of the given information, to create an exit poll that will help in predicting overall win and seats covered by a particular party.

Data Ingestion:
1. Read the dataset. Do the descriptive statistics and do null value condition check. Write an inference on it. 
2. Perform Univariate and Bivariate Analysis. Do exploratory data analysis. Check for Outliers.

Data Preparation: 
1. Encode the data (having string values) for Modelling. Is Scaling necessary here or not? Data Split: Split the data into train and test (70:30). 

Modelling:
1. Apply Logistic Regression and LDA (linear discriminant analysis).
2. Apply KNN Model and Naïve Bayes Model. Interpret the results.
3. Model Tuning, Bagging (Random Forest should be applied for Bagging) and Boosting.
4. Performance Metrics: Check the performance of Predictions on Train and Test sets using Accuracy, Confusion Matrix, Plot ROC curve and get ROC_AUC score for each model. Final Model: Compare the models and write inference which model is best/optimized.


Inference:
1. Based on these predictions, what are the insights? 

## Problem 2:

In this particular project, we are going to work on the inaugural corpora from the nltk in Python. We will be looking at the following speeches of the Presidents of the United States of America:

1. President Franklin D. Roosevelt in 1941

2. President John F. Kennedy in 1961

3. President Richard Nixon in 1973

Find the number of characters, words and sentences for the mentioned documents. 

Remove all the stopwords from all the three speeches. 

Which word occurs the most number of times in his inaugural address for each president? Mention the top three words. (after removing the stopwords) 

Plot the word cloud of each of the speeches of the variable. (after removing the stopwords)
