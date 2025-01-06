# toxic_comment_classification
This project focuses on identifying and analyzing toxic comments in social media datasets. The goal is to detect various forms of toxicity, including toxic, severe toxic, obscene, threat, insult, and identity hate speech, to contribute to safer and more inclusive online spaces.
# Project Overview
The project involves the following steps:
1. Data Collection:
Utilize two datasets: one for training and one for testing.
Data Cleaning:
Convert text to lowercase.
Remove newline characters, punctuation, and numeric characters.
Handle special characters.
Remove extra spaces.
Data Preprocessing:
Tokenize the text.
Remove stop words.
Perform lemmatization.
Exploratory Data Analysis (EDA):
Analyze the distribution of toxicity labels.
Visualize comment lengths for toxic and non-toxic comments.
Examine the correlation between different toxicity labels.
Perform Kernel Density Estimation (KDE) for numerical features.
Generate word clouds for toxic and non-toxic comments.
Feature Extraction:
Use TF-IDF vectorization to convert text data into numerical features.
Model Training:
Train multiple machine-learning models, including Logistic Regression, Random Forest, Support Vector Machine (SVM), Naive Bayes, and Gradient Boosting.
Model Evaluation:
Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
Visualize the results using bar plots and confusion matrices.
Feature Importance Analysis:
Analyze the importance of different features in the Random Forest model.
Prediction on Test Data:
Use the trained models to make predictions on the test data.
Cross-Validation:
Perform cross-validation on the training data for a more robust performance estimate.
Analysis of Test Predictions:
Analyze the distribution of predictions on the test data.
