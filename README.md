# toxic_comment_classification
This project focuses on identifying and analyzing toxic comments in social media datasets. The goal is to detect various forms of toxicity, including toxic, severe toxic, obscene, threat, insult, and identity hate speech, to contribute to safer and more inclusive online spaces.
# Project Overview
The project involves the following steps:
1. Data Collection:
- Utilize two datasets: one for training and one for testing.
2. Data Cleaning:
- Convert text to lowercase.
- Remove newline characters, punctuation, and numeric characters.
- Handle special characters.
- Remove extra spaces.
3. Data Preprocessing:
- Tokenize the text.
- Remove stop words.
- Perform lemmatization.
4. Exploratory Data Analysis (EDA):
- Analyze the distribution of toxicity labels.
- Visualize comment lengths for toxic and non-toxic comments.
- Examine the correlation between different toxicity labels.
- Perform Kernel Density Estimation (KDE) for numerical features.
- Generate word clouds for toxic and non-toxic comments.
5. Feature Extraction:
- Use TF-IDF vectorization to convert text data into numerical features.
6. Model Training:
- Train multiple machine-learning models, including Logistic Regression, Random Forest, Support Vector Machine (SVM), Naive Bayes, and Gradient Boosting.
7. Model Evaluation:
- Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
- Visualize the results using bar plots and confusion matrices.
8. Feature Importance Analysis:
- Analyze the importance of different features in the Random Forest model.
9. Prediction on Test Data:
- Use the trained models to make predictions on the test data.
10. Cross-Validation:
- Perform cross-validation on the training data for a more robust performance estimate.
11. Analysis of Test Predictions:
- Analyze the distribution of predictions on the test data.

# Tools and Technologies
The project utilizes the following tools and technologies:

- Programming Language: Python
- Libraries: pandas, NumPy, scikit-learn, nltk, matplotlib, seaborn, wordcloud, re
# Repository Structure
- Data: Data is in Zip format, download and extract raw data and preprocessed data.
- phase2.py: This file contains the Python code for the machine learning and data analysis part of the project.
- dic_code (2).py: This file contains the Python code for the data collection, cleaning, preprocessing, and exploratory data analysis (EDA) part of the project.
- README.md: This file provides a description of the project.
# Getting Started
To run this project, you will need to have Python installed along with the required libraries mentioned in the "Tools and Technologies" section. You can install the necessary libraries using pip:

`pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud`

After installing the required libraries, you can run the Python scripts.

- **Note:** The project requires the training and testing datasets to be in the same directory as the Python scripts.

# Results
The project successfully identifies and analyzes toxic comments in social media datasets. The trained machine learning models achieve high accuracy in detecting various forms of toxicity, contributing to the creation of safer and more inclusive online spaces.
