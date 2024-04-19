Spam Email Classifier
This repository contains a Python program that classifies emails as either spam or ham (non-spam) using machine learning algorithms. The program uses both Naive Bayes and Random Forest classifiers to perform the classification task. It leverages scikit-learn's CountVectorizer to transform the text data into a bag-of-words representation, which is then used as input for the classifiers.

The program evaluates the performance of both classifiers using accuracy as the primary metric:

Naive Bayes Classifier:
Score: 0.9785
Random Forest Classifier:
Score: 0.9740
These scores demonstrate that both classifiers perform well in classifying emails, with Naive Bayes achieving slightly higher accuracy.
