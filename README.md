# 🧠 Sentiment Analysis with Twitter-RoBERTa

This is a simple yet powerful sentiment analysis tool built using Hugging Face Transformers.  
It uses the `cardiffnlp/twitter-roberta-base-sentiment` model to classify input text as **Positive**, **Negative**, or **Neutral**.

---

## 🚀 Features

- Real-time sentiment prediction
- Pretrained on Twitter data
- Friendly command-line interface
- Powered by 🤗 Transformers and 🔥 PyTorch

---

## 🛠️ Installation

Install the required dependencies using pip:

```bash
pip install transformers torch
```

## 🧠 Model Info
Model: cardiffnlp/twitter-roberta-base-sentiment

Task: Sentiment Analysis

Labels: POSITIVE, NEGATIVE, NEUTRAL

```bash
sentiment-analysis/
│
├── sentiment_tool.py        # Python script with sentiment logic
├── README.md                # Project documentation
└── requirements.txt         # (Optional) List of dependencies
```