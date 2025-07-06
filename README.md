# 🇻🇳 Vietnamese Sentiment Analysis using Deep Learning

This project focuses on **sentiment analysis for Vietnamese texts** using multiple deep learning architectures.  
It covers the entire pipeline: data preprocessing, model training, evaluation, and result visualization.

---

## 💡 Project Description

- **Task**: Classify Vietnamese sentences into three sentiment categories: **Positive**, **Neutral**, and **Negative**.
- **Approach**: Apply traditional deep learning models (CNN, LSTM, CNN+LSTM) and Transformer-based model (PhoBERT).
- **Dataset**: VLSP Sentiment Corpus (social media posts and comments in Vietnamese).

---

## 🔧 Environment Setup

### 1. Create a virtual environment named `.venv`

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

### 2. Project Structure

├── BTL/
│   ├── Source/                  # Source code for training and evaluation
│   └── Report/                  # Final report (in Vietnamese)
├── results/                     # Saved model checkpoints and logs
├── vlsp_sentiment_train.csv     # Preprocessed training data
├── vlsp_sentiment_test.csv      # Preprocessed test data
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation (this file)

