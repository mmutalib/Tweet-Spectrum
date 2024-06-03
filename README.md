# Tweet-Spectrum

# Overview
Tweet Spectrum is a comprehensive project aimed at unraveling the sentiment context of Twitter (X) posts. This project conducts a comparative analysis of traditional machine learning models and large language models (LLMs) to classify tweets into positive, negative, or neutral sentiments, with a special focus on hate and profanity detection.

# Abstract
The rapid evolution of social media necessitates advanced techniques for sentiment analysis to understand public opinion and emotions expressed on platforms like Twitter. This project evaluates the accuracy and efficiency of various models in sentiment classification. We utilized a diverse dataset of tweets, preprocessing them for training and evaluation. Traditional ML models (Logistic Regression, Random Forest Classifier, Multinomial Naïve Bayes, XGBoost Classifier) are compared against cutting-edge LLMs (GPT-3, DistilBERT, RoBERTa).

Our findings highlight the strengths and limitations of each model category. While traditional ML models are less resource-intensive, they struggle with the sarcastic and informal language of Twitter. In contrast, LLMs excel in interpreting contextual and linguistic subtleties but require significant computational power. The study concludes with the development of a web application prototype for real-time sentiment analysis of Twitter texts.

# Methodology

# Data Collection and Preprocessing:
Tweets were collected and cleaned by removing special characters, extraneous columns, punctuation, and stop words using Pandas.
Exploratory Data Analysis (EDA) was performed to recognize patterns and sentiment distributions.

# Model Training:
Traditional ML models and LLMs were implemented.
Models were evaluated based on metrics like accuracy, precision, recall, and F1-score.

# Performance Comparison:
Traditional ML models showed simplicity and lower resource demands but struggled with nuanced language.
LLMs provided superior accuracy and contextual understanding at the cost of higher computational requirements.
Web Application:

A prototype web application was developed using Flask API to demonstrate real-time sentiment analysis.
# Results

# Traditional ML Models:
Effective for straightforward sentiment analysis with lower computational needs.
Limited by informal and sarcastic language.

# Large Language Models:
Superior in understanding context and nuances.
Require significant computational resources.

# Future Work
Future research will focus on expanding the dataset and exploring hybrid models that combine the strengths of traditional ML techniques and LLMs.
