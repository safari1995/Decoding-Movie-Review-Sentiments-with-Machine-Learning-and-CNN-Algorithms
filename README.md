# Decoding-Movie-Review-Sentiments-with-Machine-Learning-and-CNN-Algorithms

## Overview

This project focuses on sentiment analysis (polarity detection) of movie reviews using deep learning and machine learning techniques. We aim to automatically classify text into positive or negative sentiments based on user reviews. By leveraging Multi channel Convolutional Neural Networks (CNN), Support vector machine (SVM) , Random Forest (RF) , Decision Tree Classifier (DT) and CatBoost Classifier (CAT).

## Data
We use polarity dataset v2.0 from the https://www.cs.cornell.edu/people/pabo/movie-review-data/ .
It has 1000 positive and 1000 negative processed reviews.We use 80 percent of data for train and 20 percent for test.





## Key Features and Result

- **Sentiment Classification**: Our models predict whether a movie review expresses a positive or negative sentiment.
- **Preprocessing**: We preprocess the text data by eliminating stop words and tokenize it using NLTK library.
- **Model Comparison**: After traning models with train data, we comprise models accuracy by test data.
  - **SVM**: Achieved an accuracy of **88%** and an F1-score of **88%**.
  - **Multi Channel CNN**: Achieved an accuracy of **85%**.
  - **CAT**: Recorded an accuracy of **82%**.
  - **RF**: Recorded an accuracy of **80%**.
  - **DT**: Recorded an accuracy of **62%**.
  
