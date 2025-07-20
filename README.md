# 🧠 Natural Language Processing (NLP) with Python

This repository contains a comprehensive Jupyter Notebook that explores essential Natural Language Processing (NLP) techniques using Python. It covers everything from basic preprocessing to advanced topic modeling.

---

## 📌 Table of Contents

1. [🔧 Libraries](#-libraries)
2. [🧼 Text Preprocessing](#-text-preprocessing)
3. [🔎 POS Tagging & Named Entity Recognition](#-pos-tagging--named-entity-recognition)
4. [📊 Sentiment Analysis](#-sentiment-analysis)
5. [🧮 Vectorizing Text](#-vectorizing-text)
6. [📚 Topic Modeling](#-topic-modeling)

---

## 🔧 Libraries

The following Python libraries are used throughout the notebook:
- `nltk`
- `spacy`
- `re`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `textblob`
- `sklearn`
- `gensim`
- `wordcloud`

---

## 🧼 Text Preprocessing

Fundamental steps to clean and prepare raw text for analysis:

- **Lowercasing**  
  Convert all text to lowercase to ensure uniformity.

- **Removing Stop Words**  
  Eliminate common words (like "the", "and", "is") that add little value.

- **Regular Expressions (Regex)**  
  Extract or clean specific text patterns using `re.search`, `re.sub`, etc.

- **Tokenization**  
  Split text into individual words or tokens.

- **Stemming**  
  Reduce words to their root forms (e.g., "running" → "run").

- **Lemmatization**  
  More accurate root-word extraction using context-aware algorithms.

- **N-Grams**  
  Create sequences of N items (words or characters) to capture context.

---

## 🔎 POS Tagging & Named Entity Recognition

- **Part-of-Speech (POS) Tagging**  
  Label each word with its grammatical role using tools like `nltk` or `spaCy`.

- **Named Entity Recognition (NER)**  
  Identify proper names, dates, locations, etc., using `spaCy`'s NER pipeline.

---

## 📊 Sentiment Analysis

Understand the emotional tone of the text using:

- **TextBlob**  
  Quick polarity and subjectivity scoring.

- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**  
  Rule-based model optimized for social media text.

---

## 🧮 Vectorizing Text

Convert text into numerical format for machine learning:

- **Bag of Words (BoW)**  
  Represents text by word frequency in a fixed vocabulary.

- **TF-IDF (Term Frequency - Inverse Document Frequency)**  
  Weights words by frequency across documents to emphasize importance.

---

## 📚 Topic Modeling

Discover hidden thematic structures in text:

- **LDA (Latent Dirichlet Allocation)**  
  Probabilistic model that assigns topics to words.

- **LSA (Latent Semantic Analysis)**  
  Decomposes term-document matrix to reveal relationships between terms and topics.
