# Sentiment Analysis on Restaurant Reviews: Using Machine Learning Approach 

== Instructions ==

Four Jupyter Notebook files are used in this NLP project.

'res_EDA': 

This is used for data cleaning and data visualization before and after text preprocessing.

Running this file will create four CSV files (X_train, y_train, X_test, y_test) for training and testing.

'res_logistics_regression': 

This is used to compare the performance of the baseline model and advanced model in which the baseline model is the logistic regression with count vectorizer while the advanced version is the logistic regression with TF-IDF vectorizer, grid search and 10-fold cross-validation.

'res_naive_bayes':

This is used to compare the performance of the baseline model and advanced model in which the baseline model is the Naive Bayes with count vectorizer while the advanced version is the Naive Bayes with TF-IDF vectorizer and 10-fold cross-validation.

'res_support_vector_machines':

This is used to compare the performance of the baseline model and advanced model in which the baseline model is the support vector machines model with count vectorizer while the advanced version is the support vector machines model with TF-IDF vectorizer, grid search and 10-fold cross-validation.

== Important Note == 

Please run the 'res_EDA' Jupyter Notebook first if you do not have the X_train, y_train, X_test, y_test CSV files.

== References ==

The dataset: https://huggingface.co/datasets/pachequinho/restaurant_reviews
