# Sentiment Analysis NLP

Mini project exploring sentiment classification using traditional ML approaches with scikit-learn.

## Overview

Compares three classifiers — **Logistic Regression**, **Random Forest**, and **Support Vector Machine** — on a sentiment analysis task using text features at multiple levels:

- Bag-of-words (unigram)
- Bigrams
- GloVe word embeddings (pre-trained 100-dimensional)

## Files

| File | Description |
|---|---|
| `MiniProject3.ipynb` | Main notebook with full experiments and results |
| `MiniProject3 - Copy.ipynb` | Duplicate copy |
| `*.png` | Confusion matrices, word clouds, average length chart, top words charts |

## Features

- **Text preprocessing**: tokenization, stopword removal
- **Feature extraction**: CountVectorizer (unigram + bigram), GloVe embeddings
- **Models**: Logistic Regression, Random Forest, SVM
- **Evaluation**: confusion matrices, classification metrics

## Prerequisites

- Python 3.x
- `scikit-learn`, `matplotlib`, `seaborn`, `nltk`
- GloVe embeddings (`glove.2024.wikigiga.100d.zip`) — not included in this repo; download separately and extract to `glove.2024.wikigiga.100d/`

## Repo

Published at [github.com/PancratiusV/sentiment-analysis-nlp](https://github.com/PancratiusV/sentiment-analysis-nlp).

## Notes

The GloVe embeddings file (`glove.txt`, ~1.6 GB) is excluded from this repo via `.gitignore` due to size. Download and extract it before running the notebook.
