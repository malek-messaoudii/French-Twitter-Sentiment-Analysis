# French Twitter Sentiment Analysis

## Project Description

This project implements a sentiment analysis system capable of automatically classifying French tweets as having positive or negative sentiment. The model uses Natural Language Processing (NLP) techniques and machine learning with TF-IDF (Term Frequency-Inverse Document Frequency) for text vectorization to analyze tweet content.

## Objectives
- Clean and preprocess French text data using NLP techniques

- Build a high-performance sentiment classification model using TF-IDF vectorization

- Deploy an intuitive user interface with Gradio

- Analyze most frequent words for each sentiment category

## Dataset
Source : The dataset comes from Kaggle: French Twitter Sentiment Analysis

## Characteristics
- Size: ~100,000 French tweets

- Columns: text: Tweet content

- label: Sentiment (0 = Negative, 1 = Positive)

- Language: French

## Technical Approach

### TF-IDF Vectorization Technique
This project utilizes TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction from text data:

- Term Frequency (TF): Measures how frequently a term appears in a document

- Inverse Document Frequency (IDF): Measures how important a term is across the entire corpus

- Combination: TF-IDF weights words by their importance, reducing the impact of common words

### Machine Learning Pipeline

- Text Preprocessing: Cleaning and normalization of French text

- TF-IDF Vectorization: Converting text to numerical features

- Logistic Regression: Classification model training

- Model Evaluation: Performance assessment and validation

## Technologies Used

- Python 3.11

- Pandas - Data manipulation and analysis

- Scikit-learn - Machine Learning (TF-IDF, Logistic Regression)

- NLTK - Natural Language Processing for French text

- Matplotlib/Seaborn - Data visualizations

- Gradio - Web interface deployment

- WordCloud - Frequent words visualization

## Quick Start

### Installation
 ```
 git clone https://github.com/malek-messaoudii/French-Twitter-Sentiment-Analysis.git
 cd french-twitter-sentiment-analysis
 pip install -r requirements.txt
```

