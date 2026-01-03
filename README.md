# 📰 Fake News Detection with Machine Learning

## Overview
This project focuses on detecting **fake** and **real** news articles using **machine learning** and **natural language processing (NLP)** techniques in Python.  
The goal is to reduce misinformation by automatically classifying news content.

---

## Dataset
The dataset contains:
- **title** – news headline  
- **text** – news content  
- **label** – `0: Fake`, `1: Real`  

The `Unnamed: 0` column is removed as it is only an index.

---

## Methods
- Text preprocessing and TF-IDF vectorization  
- Machine learning models:
  - Random Forest Classifier  
  - Support Vector Machine (SVM)  
- Sentiment Analysis using **TextBlob**

---

## Results
- **Random Forest Accuracy:** 90%  
- **SVM Accuracy:** 88%  

Random Forest showed more balanced and higher overall performance.

---

## Sentiment Analysis
Text sentiment is analyzed using **TextBlob**:
- **Polarity:** measures positive/negative emotion  
- **Subjectivity:** measures objectivity level  

---

## Conclusion
Machine learning models can effectively detect fake news.  
Random Forest performed best, and sentiment analysis provided additional insights.

