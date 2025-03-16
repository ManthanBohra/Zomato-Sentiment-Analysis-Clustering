# **Zomato Sentiment Analysis & Clustering**

## 📌 Project Overview

This project focuses on analyzing customer reviews from Zomato to extract sentiments and group similar reviews using clustering techniques. By leveraging Natural Language Processing (NLP) and Machine Learning, we aim to gain insights into customer sentiments, identify key trends, and improve business decision-making.

## 🚀 Objectives

Perform sentiment analysis on customer reviews to classify them as positive, neutral, or negative.

Use unsupervised clustering techniques to group similar reviews.

Identify key factors affecting restaurant ratings.

Provide data-driven insights to enhance customer experience.

## 🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, NLTK, Scikit-learn, Matplotlib, Seaborn

Machine Learning: Sentiment Classification (Logistic Regression, Naïve Bayes, Random Forest)

Clustering Algorithms: K-Means, DBSCAN

Visualization: Power BI, Matplotlib, Seaborn

Database: MySQL (if storing structured data)

## 📂 Dataset

Source: Zomato customer review dataset (can be scraped from Zomato or obtained from open-source datasets)

## Features:

Review Text: Customer feedback

Rating: Given by the customer (1-5 stars)

Sentiment Label: Classified as Positive, Neutral, or Negative

Restaurant Name: Name of the reviewed restaurant

Date: Date of the review

## 📊 Methodology

Data Collection & Preprocessing:

Data scraping or using an existing dataset

Cleaning text data (removing stopwords, punctuation, etc.)

Tokenization & Lemmatization

## Sentiment Analysis:

Using VADER Sentiment Analyzer for rule-based sentiment classification

Training a ML model (Naïve Bayes, Logistic Regression) for supervised sentiment classification

## Clustering Analysis:

Applying TF-IDF Vectorization for text representation

Performing K-Means Clustering to group similar reviews

Using DBSCAN for density-based clustering

## Visualization & Insights:

Creating Power BI dashboards to present sentiment trends

Analyzing most frequent words in positive/negative reviews using word clouds

Identifying key customer concerns and satisfaction factors

## 📈 Results & Insights

The model achieved high accuracy in classifying sentiments.

Clustering helped segment customer reviews based on common themes.

Negative reviews revealed key pain points like service quality, food taste, and pricing issues.

Positive reviews highlighted aspects like ambience, friendly staff, and quick service.

## 🔥 Future Scope

Incorporate deep learning (LSTM, BERT) for better sentiment classification.

Perform topic modeling (LDA) to extract key themes from reviews.

Build a real-time sentiment dashboard using Power BI.

## 📜 Conclusion

This project provides valuable insights into customer sentiments on Zomato. The sentiment analysis and clustering techniques help restaurants understand customer feedback, improve their services, and enhance customer satisfaction.
