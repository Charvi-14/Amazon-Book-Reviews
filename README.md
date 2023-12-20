# Sentiment-Prediction-
using the sci-kit learn library to predict sentiment of amazon book reviews

BASIC OVERVIEW:
-Creating classes for code reusability and modularity
-Loading the 'Books_small_10000.json"
-We are concerned about the 'reviewText' and 'overall' fields only in a json file line
-Preparing the data by using test_train_split form sklearn
-Using the bag of words vectorization to convert text to numerical data which can be used in model fitting
-We prefer using the TfidfVectrorizer to account for the words that affect the sentiment
-The models used are: Linear SVM, Decision Tree and Logisitic Regression
-Evaluating each models f1 score (better while using Tfidf rather than CountVectroizer
-Doing a Qualitative Analysi
