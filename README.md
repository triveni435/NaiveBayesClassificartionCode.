#  Email Spam Classification using Naive Bayes

## 📌 Project Overview

This project implements an Email Spam Classification system using Natural
Language Processing (NLP) and the Naive Bayes Machine Learning algorithm.

The model classifies email messages into two categories:

- Spam
- Not Spam (Ham)

## 🎯 Objective

The objective of this project is to understand how text data can be converted
into numerical features and used to build a Machine Learning classification
model for detecting spam emails.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorization
- Naive Bayes
- Jupyter Notebook

## 📊 Dataset

The project uses a sample dataset containing 6 email messages:

- 3 Spam emails
- 3 Non-Spam emails

The dataset includes:

- Email Subject
- Email Text
- Spam Label

## 🔄 Project Workflow

1. Create and load the email dataset
2. Convert the data into a Pandas DataFrame
3. Perform text preprocessing
4. Convert email text into numerical features using TF-IDF
5. Train the Naive Bayes classification model
6. Predict email categories
7. Evaluate the model using classification metrics

## 🤖 Machine Learning Model

### Bernoulli Naive Bayes

The project uses the `BernoulliNB` algorithm from Scikit-learn for binary text
classification.

TF-IDF is used to represent the email text as numerical features before
training the classification model.

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

### Training Result

The model achieved **100% accuracy on the training dataset**.

Because the evaluation was performed on the same small dataset used for
training, this result should not be considered a measure of real-world
generalization.

## 📁 Project Structure

```text
NaiveBayesClassificationCode/
│
├── NaiveBayesClassificartionCode.ipynb
└── README.md
