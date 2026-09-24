# NLP Text Classification & Sentiment Analysis

## Overview

This project applies natural language processing and machine learning to classify 8,002 social media comments into five categories:

- Positive
- Negative
- Neutral
- Objective
- Objective-OR-neutral

The analysis uses text vectorization and a Support Vector Machine (SVM) to classify the comments.

## Methods

- Python
- Natural Language Processing (NLP)
- CountVectorizer
- Unigrams and bigrams
- Linear Support Vector Machine (LinearSVC)
- GridSearchCV
- Cross-validation
- Train/test split

## Modeling

The text was converted into numerical features using CountVectorizer. A LinearSVC model was then trained to classify comments into the five categories.

GridSearchCV was used to test different combinations of model and text-processing parameters and identify the best-performing configuration.

The best cross-validation score was approximately 44.65%.

## Dataset

The dataset contains 8,002 social media comments across five classification categories.

## Business Application

Automated text classification can help organizations analyze large volumes of customer or social media feedback without manually reviewing every comment.

Potential applications include:

- Customer feedback monitoring
- Social media analysis
- Product feedback analysis
- Customer experience research

## Tools

Python | Scikit-learn | Pandas | NLP | Machine Learning
