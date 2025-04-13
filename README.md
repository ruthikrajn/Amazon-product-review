# 🛍️ Amazon Product Review Sentiment Analysis

A Natural Language Processing (NLP) project that analyzes Amazon product reviews using traditional (VADER) and transformer-based (RoBERTa) sentiment analysis techniques. This project compares sentiment results from both models and visualizes their insights based on user ratings.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Sentiment Analysis with VADER](#sentiment-analysis-with-vader)
- [Sentiment Analysis with RoBERTa](#sentiment-analysis-with-roberta)
- [Model Comparison](#model-comparison)
- [Visualizations](#visualizations)


---

## 🧠 Overview

This project performs sentiment analysis on **Amazon product reviews** using:

1. **VADER** (Valence Aware Dictionary and sEntiment Reasoner) – rule-based sentiment analysis tool
2. **RoBERTa** – a transformer-based pre-trained model (`cardiffnlp/twitter-roberta-base-sentiment`)

The goal is to compare sentiment scores from both models, visualize the results, and gain insights into product perception by users.

---

## 🛠️ Tech Stack

- **Python**
- **NLTK** for tokenization, POS tagging, and VADER
- **Transformers (HuggingFace)** for RoBERTa
- **Matplotlib**, **Seaborn** for visualization
- **Pandas**, **NumPy** for data manipulation
- **Google Colab** for execution

---

## 🔍 Exploratory Data Analysis (EDA)

- Loaded and previewed the dataset (`Reviews.csv`)
- Reviewed distribution of review scores (1 to 5 stars)
- Visualized the count of reviews using bar plots


