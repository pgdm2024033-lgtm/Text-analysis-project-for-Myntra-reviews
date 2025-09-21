# Project Title

Myntra reviews

## Background / Motivation
 sentiment analysis of app reviews, extracting themes, etc.

## Data
- Source of data (Google Play scraper, etc.)  
- Size (number of rows, columns)  
- Fields/Columns description (`text`, `lowercase_text`, `tokenized_text`, etc.)  

## Preprocessing
Describe the preprocessing steps:
1. Removing missing rows from Text
2. Lowercasing  
3. Removing special characters  
4. Tokenization  
5. Stopword removal  

Libraries used (NLTK, re, pandas), and any cleaning decisions

## Sentiment Analysis

- Text column used No special character   
- Library used TextBlob  
- How sentiment score & category are determined (thresholds: >0 = positive, <0 = negative, =0 neutral)  

## Topic Modeling

- Method (TF-IDF + Non-negative Matrix Factorization (NMF))  
- How text was prepared for modeling  
- Number of topics  
- How the top words per topic are extracted  


