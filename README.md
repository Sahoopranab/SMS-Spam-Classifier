# SMS-Spam-Classifier
MS Spam Classifier  This repository contains a Python implementation of a text classification model to distinguish between spam and non-spam SMS messages using data science techniques.

Key Features:

Data Importing: Imports SMS data from a CSV file for model training and evaluation.

Data Preprocessing: Cleans and prepares the data by handling missing values and unnecessary columns.

Model Selection: Utilizes the Naive Bayes classifier (MultinomialNB) for its efficiency in text classification tasks.

Vectorization: Converts text data into numerical feature vectors using CountVectorizer.

Model Evaluation: Splits the dataset into training and testing sets for evaluating model performance.

User Interaction: Provides a simple interface for users to input a message and receive a prediction of whether it's spam or non-spam.

Usage:

Import the required libraries.
Load the SMS dataset.
Preprocess the data by handling missing values and unnecessary columns.
Select and train the classification model using Multinomial Naive Bayes.
Interact with the model by inputting a message to classify it as spam or non-spam.

Dependencies:

pandas,
numpy,
scikit-learn
