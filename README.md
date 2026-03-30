# Naive_Bayes_Algorithm_demonstration
Naive Bayes Spam Classification Project
This project demonstrates the implementation of Naive Bayes Classifier for spam detection using both manual calculation and scikit-learn.
Project Overview
The project is divided into two parts:
Part 1: Manual Multinomial Naive Bayes (from scratch)
Implemented a Multinomial Naive Bayes classifier from scratch to classify messages as Spam or Not Spam.

Built a small custom dataset of 4 messages
Created a vocabulary and calculated word frequencies per class
Computed prior probabilities and likelihoods with Laplace smoothing
Classified a new message ("buy now") step-by-step

Part 2: Scikit-learn Implementation
Applied the MultinomialNB model on a larger dataset (10 messages) using sklearn.

Performed text preprocessing using CountVectorizer
Split data into training and testing sets
Trained the Naive Bayes model
Evaluated model performance using accuracy
Made predictions on a custom message ("Congratulations, you've won a free vacation")

Key Concepts Demonstrated
Tokenization and vocabulary creation
Bag-of-Words representation
Prior and conditional probability calculation
Laplace (Add-One) smoothing to handle zero probabilities
Multinomial Naive Bayes algorithm
Text vectorization using CountVectorizer
Model training and evaluation with scikit-learn

Technologies Used
Python
Pandas
Scikit-learn (CountVectorizer, MultinomialNB)
Matplotlib / Seaborn (optional for visualization)
