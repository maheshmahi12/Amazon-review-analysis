Sentiment Analysis of Amazon Product Reviews

Project Overview

This project focuses on the sentiment analysis of Amazon product reviews. The primary goal is to classify reviews based on their sentiment ratings using natural language processing (NLP) and machine learning techniques. The dataset includes reviews from various product categories, which are preprocessed and analyzed to build a predictive model.

Dataset

Training Dataset Size: 6000 reviews
Testing Dataset Size: 2000 reviews
Features:
brand: Product brand identifier
primaryCategories: Product category
reviews.numHelpful: Number of helpful votes for the review
reviews.rating: Sentiment rating (target variable)
reviews.text: Text of the review
Objectives

Data Cleaning & Preprocessing: Handle missing values, clean and preprocess text data.
Exploratory Data Analysis (EDA): Understand the distribution of sentiment ratings and most common words in reviews.
Feature Extraction: Use TF-IDF vectorization to convert text data into numerical features.
Model Training & Evaluation: Train and evaluate a Logistic Regression model to predict sentiment ratings.
Model Optimization: Use GridSearchCV to tune hyperparameters for improved model performance.
Key Findings

Most Common Words: Words like "batteries", "great", "good", and "tablet" appeared frequently in the reviews.
Least Common Words: Words like "construction", "buckle", and "pit" were among the least common.
Model Performance: The initial Logistic Regression model achieved an accuracy of 68.33%. After hyperparameter tuning, the accuracy improved to 69.75%.
Visualization

Sentiment Distribution: A bar chart showing the distribution of sentiment ratings in the training data.
Word Cloud: A word cloud visualization of the most common words in the reviews.
Technologies Used

Programming Language: Python
Libraries: pandas, matplotlib, sklearn, nltk, re, collections, wordcloud
Author

Mahesh Yagandla

