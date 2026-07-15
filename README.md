# 📈 Stock Market Sentiment Analysis Using Twitter Data with FinBERT

## Final Year Project

This project presents a **Stock Market Sentiment Analysis System** that predicts the sentiment of stock-related tweets using the **FinBERT** deep learning model. The objective is to analyze public opinion on financial markets by classifying tweets into **Positive**, **Negative**, or **Neutral** sentiments, providing insights that can support investment decisions and market trend analysis.

---

## 📖 Project Overview

Financial markets are heavily influenced by public opinion, news, and social media discussions. Twitter has become one of the most popular platforms where investors and traders share their views on stocks and market events.

This project utilizes **FinBERT**, a transformer-based language model specifically trained on financial text, to perform sentiment analysis on stock market tweets. Compared to traditional sentiment analysis models, FinBERT provides higher accuracy for finance-related language and terminology.

---

## 🎯 Objectives

- Collect stock-related tweets from Twitter.
- Preprocess tweet text for analysis.
- Perform sentiment classification using the FinBERT model.
- Classify tweets into:
  - Positive
  - Negative
  - Neutral
- Visualize sentiment distribution and analysis results.
- Provide insights into market sentiment based on social media data.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Transformers (Hugging Face)
- PyTorch
- FinBERT
- Scikit-learn

---

## 📂 Project Structure

```
Stock-Market-Sentiment-Analysis/
│
├── data/
│   ├── raw_tweets.csv
│   └── processed_tweets.csv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── models/
│   └── finbert_model/
│
├── results/
│   ├── sentiment_distribution.png
│   └── prediction_results.csv
│
├── requirements.txt
├── README.md
└── main.py
```

---

## ⚙️ Methodology

1. Collect stock-related tweets.
2. Clean and preprocess tweet text.
3. Tokenize text using the FinBERT tokenizer.
4. Load the pretrained FinBERT model.
5. Predict tweet sentiment.
6. Store prediction results.
7. Visualize overall sentiment distribution.

---

## 🤖 FinBERT Model

FinBERT is a BERT-based language model that has been pretrained and fine-tuned on financial text. It is specifically designed for financial sentiment analysis and is capable of understanding finance-specific terminology better than general-purpose language models.

The model classifies each tweet into one of the following categories:

- 🟢 Positive
- 🔴 Negative
- ⚪ Neutral

---

## 📊 Expected Output

The system generates:

- Sentiment prediction for each tweet
- Overall sentiment distribution
- Data visualization charts
- CSV file containing prediction results

Example:

| Tweet | Sentiment |
|--------|-----------|
| Tesla stock is performing exceptionally well! | Positive |
| The market is crashing today. | Negative |
| Investors are waiting for earnings reports. | Neutral |

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/stock-market-sentiment-analysis.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

---

## 📈 Applications

- Stock market analysis
- Financial research
- Investment decision support
- Market trend monitoring
- Social media analytics

---

## 📚 References

- Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2019). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.
- Araci, D. (2019). FinBERT: Financial Sentiment Analysis with Pre-trained Language Models.
- Hugging Face Transformers Library

---

## 👨‍🎓 Author

**Final Year Project**

**Title:** *Stock Market Sentiment Analysis Using Twitter Data with FinBERT*

Developed as part of the requirements for the completion of the Final Year Project.
