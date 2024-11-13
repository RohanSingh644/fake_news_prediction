

---

# Fake News Prediction

## Project Overview

The **Fake News Prediction** project is a machine learning solution for detecting fake news articles. With misinformation spreading quickly across digital platforms, this project aims to classify news articles as either "fake" or "real" by analyzing their content. This project leverages Python libraries for data processing, feature extraction, and model building to achieve high accuracy in classification.

## Libraries Used

- **NumPy**: For numerical operations and array handling.
- **Pandas**: For efficient data manipulation and analysis.
- **Regular Expressions (re)**: To clean text data by removing unwanted characters.
- **NLTK (Natural Language Toolkit)**: Used for stopword removal and stemming to preprocess text data.
- **Scikit-Learn (sklearn)**: For feature extraction, model building, and evaluation.

## Key Features

- **Data Cleaning and Preprocessing**:
  - Removes irrelevant characters, punctuation, and stopwords from the text data.
  - Applies stemming using **PorterStemmer** to reduce words to their base forms.

- **Feature Extraction**:
  - Uses **TfidfVectorizer** to convert text data into numerical form by calculating Term Frequency-Inverse Document Frequency (TF-IDF) scores for each word.

- **Model Training and Testing**:
  - Splits data into training and testing sets using **train_test_split**.
  - Implements **Logistic Regression** to classify news articles as "fake" or "real".

- **Evaluation**:
  - Measures model performance with **accuracy_score** to assess classification accuracy.


