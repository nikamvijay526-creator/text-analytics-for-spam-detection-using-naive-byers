📩 Spam–Ham Detection using Naive Bayes Classifier
📌 Project Overview

This project implements a Spam Detection System using the Naive Bayes classification algorithm.

The model classifies SMS messages into:

* Spam 🛑 – Unwanted or promotional messages

* Ham ✅ – Legitimate messages

Text data is converted into numerical features using Bag-of-Words / TF-IDF, and a Multinomial Naive Bayes classifier is trained to predict message categories.

🎯 Problem Statement

With the rapid growth of digital communication, spam messages have become a major issue.
The goal of this project is to build a machine learning model that automatically detects whether a message is spam or not.

📂 Dataset

The dataset used is the SMS Spam Collection Dataset commonly available on Kaggle.

It contains:

* 5,000+ SMS messages

* Label column (spam or ham)

* Message text column

⚙️ Technologies Used

* Python 🐍

* Pandas

* NumPy

* Scikit-learn

* Matplotlib / Seaborn (for visualization)

* Natural Language Processing (NLP)

🧠 Machine Learning Model
1️⃣ Text Preprocessing

* Convert text to lowercase

* Remove punctuation

* Remove stopwords

* Tokenization

2️⃣ Feature Extraction

* CountVectorizer (Bag-of-Words)
   OR

* TF-IDF Vectorizer

3️⃣ Model Training

* Multinomial Naive Bayes Classifier

4️⃣ Model Evaluation

* Accuracy

* Confusion Matrix

* Precision

* Recall

* F1-score
