# 📰 Media Bias Detection in News Headlines

A Natural Language Processing project that classifies news headlines into three synthetic framing categories: **Left, Neutral, and Right**.

The project explores text preprocessing, sentence embeddings, semantic search using FAISS, traditional machine learning, and transformer-based text classification.

---

## 📌 Project Overview

The goal of this project is to experiment with automatic classification of news headlines based on linguistic framing tendencies.

The three labels used in the dataset are:

- `left`
- `neutral`
- `right`

These labels represent **synthetic ideological/framing categories created for the project**. They should not be interpreted as objective political truth or verified political classifications.

---

## 🔄 Project Workflow

```text
News Headlines
      ↓
Text Cleaning
      ↓
SBERT Embeddings
      ↓
EDA / Word Associations
      ↓
FAISS Semantic Search
      ↓
Baseline Logistic Regression
      ↓
DistilBERT Classification
      ↓
Model Evaluation
