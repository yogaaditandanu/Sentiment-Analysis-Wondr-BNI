# Sentiment-Analysis-Wondr-BNI
🏦 Wondr by BNI – Sentiment Analysis Project
📊 Analyzing customer feedback to enhance digital banking experience
🧭 Project Overview

This project aims to analyze customer reviews from the Wondr by BNI app on Google Play Store using Natural Language Processing (NLP).
It identifies user sentiment (positive / negative) and extracts insights to help understand customer experience and app performance.

🔍 Key Steps

Data Scraping – Collected 63K+ reviews using google-play-scraper

Data Cleaning – Handled nulls, duplicates, and slang normalization

Preprocessing – Tokenization, stopword removal, and stemming (Bahasa Indonesia)

Sentiment Analysis – Using Indonesian lexicon-based approach

Modeling & Evaluation – Compared Logistic Regression, Naive Bayes, and Random Forest

📈 Results
Metric	Value
Positive Sentiment	62%
Negative Sentiment	38%
Best Model	Logistic Regression
Accuracy	~90%
💬 Key Insights

Most positive words: mudah, cepat, bagus, tampilan, aman

Most negative words: lemot, error, login, gagal, lambat

Positive feedback emphasizes usability & modern interface,
while negative feedback points to stability and access issues.

🛠️ Tech Stack

Python (pandas, scikit-learn, nltk, Sastrawi, google-play-scraper, wordcloud, matplotlib)

Jupyter / Google Colab

NLP & Lexicon-based Sentiment Analysis

Visualization: matplotlib, wordcloud

💡 Future Development

Deploying a Streamlit dashboard for interactive sentiment exploration

Integrating topic modeling (LDA) for deeper insight into user pain points

Building a monitoring system for ongoing app review trends

👤 Author

Yoga Adi
ODP General Banking – PT Bank Negara Indonesia (Persero) Tbk
Passionate in Data Analytics, Digital Banking, and Product Development

🏷️ Tags

#BNI #DigitalBanking #DataAnalytics #SentimentAnalysis #CustomerExperience #MachineLearning #Python
