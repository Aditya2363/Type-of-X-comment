This project analyzes Twitter data to determine the sentiment of tweets.

Here's a breakdown of the steps:

Data Loading and Preprocessing: The code loads the Twitter data, assigns column names, checks for missing values, and converts the target variable (sentiment) to a binary representation (0 for negative, 1 for positive).
Text Stemming: The stemming function is applied to the 'text' column to reduce words to their root form and remove stop words.
Data Splitting: The data is split into training and testing sets.
Feature Extraction: The TfidfVectorizer is used to convert the text data into numerical features.
Model Training: A Logistic Regression model is trained on the training data.
Model Evaluation: The accuracy of the trained model is evaluated on both the training and testing data.
Model Saving and Loading: The trained model is saved using pickle and then loaded.
Prediction: Finally, the loaded model is used to make a prediction on a new data point from the test set.
