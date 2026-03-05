# senitiment-Analysis
**Restaurant Reviews Sentiment Analysis (Positive vs Negative)**

## Project Overview

This project builds a sentiment analysis model to classify restaurant reviews as Positive or Negative
using Python and NLP techniques.

## Problem Statement

Classify restaurant reviews into positive/negative sentiment to support data-driven understanding of
customer feedback.

## What I Did
Collected review data from a CSV file (e.g., restaurant_reviews.csv ) containing review text (and
optionally rating).

Cleaned and preprocessed text (removed noise, tokenization, stopwords removal, normalization
such as lowercasing/lemmatization).

Converted text into numerical features using Bag-of-Words and/or TF-IDF.

Trained a sentiment classifier (e.g., Logistic Regression / SVM / Naive Bayes) and evaluated model
performance.

Visualized insights using plots like sentiment distribution and word cloud.

## Tech Stack

Python

Libraries: NLTK, TextBlob, scikit-learn, pandas, NumPy, Matplotlib/Seaborn

## Visuals (Examples)

Sentiment value counts (Positive vs Negative)

Word cloud of frequent terms in reviews

Frequent-word analysis chart (e.g., "food", "place", "restaurant")

<img width="810" height="865" alt="Screenshot 2026-03-05 115209" src="https://github.com/user-attachments/assets/e85396d0-ee10-4259-875c-537bed5cbc47" />

## How to Run (Local)

1. Clone the repo
```bash
 
git clone https://github.com/girishavallabhaneni/sentiment-Analysis.git

cd sentiment-Analysis

2.Create environment + install dependencies

python -m venv venv

# Windows: venv\Scripts\activate

# macOS/Linux: source venv/bin/activate

pip install -r requirements.txt

3.Run the notebook / script

Open the notebook and run all cells (recommended), or run your training script if available.

-Project Structure

├─ data/
│  └─ restaurant_reviews.csv
├─ notebooks/
│  └─ sentiment_analysis.ipynb
├─ src/
│  ├─ preprocess.py
│  ├─ train.py
│  └─ predict.py
├─ outputs/
│  ├─ wordcloud.png
│  └─ sentiment_counts.png
├─ requirements.txt
└─ README.md

Results:

The analysis shows a mix of positive and negative feedback, and the insights are supported with visualization for clearing interpretation.


