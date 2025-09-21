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
1. Removing missing rows from `text`  
2. Lowercasing  
3. Removing special characters  
4. Tokenization  
5. Stopword removal  

Libraries used (NLTK, re, pandas), and any cleaning decisions (which characters removed, etc.).

## Sentiment Analysis

- Which text column used (e.g. `no_special_chars_text`)  
- Library used (TextBlob)  
- How sentiment score & category are determined (thresholds: >0 = positive, <0 = negative, =0 neutral)  

## Topic Modeling

- Method (TF-IDF + Non-negative Matrix Factorization (NMF))  
- How text was prepared for modeling  
- Number of topics  
- How the top words per topic are extracted  

## Usage
Steps to run the project / reproduce results:
```bash
# clone repo
git clone <your-repo-url>
cd <repo-folder>

# install dependencies
pip install -r requirements.txt

# (if applicable) download NLTK stopwords:
python -c "import nltk; nltk.download('stopwords')"

# Run preprocessing
python preprocess.py

# Sentiment analysis
python sentiment_analysis.py

# Topic modeling & visualizations
python topic_modeling.py
