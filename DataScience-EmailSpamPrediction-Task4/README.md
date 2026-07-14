# Email Spam Detection using Machine Learning

## Objective

Build a machine learning model that classifies SMS messages as either Spam or Ham (Not Spam) using Natural Language Processing (NLP) and supervised machine learning techniques.

## Dataset

- Dataset: SMS Spam Collection Dataset
- Source: Kaggle
- Link: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Joblib

## Steps Performed

1. Imported the dataset
2. Cleaned and preprocessed the text data
3. Converted labels (Ham = 0, Spam = 1)
4. Removed missing and duplicate values
5. Split the dataset into training and testing sets
6. Converted text into numerical features using TF-IDF Vectorization
7. Trained a Multinomial Naive Bayes classifier
8. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
9. Tested the model on custom SMS messages
10. Saved the trained model and vectorizer

## Outcome

Successfully developed an Email Spam Detection model capable of classifying SMS messages as Spam or Ham with high accuracy.

## Author

Neerav Bora
