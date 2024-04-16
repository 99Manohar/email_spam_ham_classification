# email_spam_ham_classification
# Preprocessing Steps:
# Importing the Dataset: The dataset is imported using Pandas' read_csv function.
# Text Preprocessing:
# Removed stopwords.
# Removed special characters using regular expressions.
# Converted all text to lowercase for consistency.
# Feature Engineering:
# Utilized Bag-of-Words model for feature extraction using CountVectorizer from sklearn.feature_extraction.text. Limited the maximum number of features to 2500.
# Model Training:
# Employed a Random Forest classifier from sklearn.ensemble for the classification task.
# Evaluation:
# Test Accuracy: Achieved an accuracy of 98.57% on the test set.
# Training Accuracy: Achieved an accuracy of 99.93% on the training set.
