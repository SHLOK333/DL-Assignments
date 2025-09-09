# 🗳️ Reddit Political Sentiment Analysis with LSTM

## 📌 Project Overview
This project performs **sentiment analysis** on political discussions from Reddit. We fetch live data from the **r/politics** subreddit, label it with sentiment, train an LSTM model, and visualize sentiment trends for key political figures.

---

## 🔄 Project Flow

+----------------+
|  Reddit API    |
| (Data          |
|  Collection)   |
+-------+--------+
|
v
+-------+--------+
| Raw Reddit     |
| Posts          |
| (title, body,  |
|  score, date)  |
+-------+--------+
|
v
+-------+--------+
| Sentiment      |
| Labeling       |
| (VADER)        |
+-------+--------+
|
v
+-------+--------+
| Preprocessing  |
| (cleaning,     |
|  tokenization) |
+-------+--------+
|
v
+-------+--------+
|  LSTM Model    |
|  Training      |
+-------+--------+
|
v
+-------+--------+
|   Trained      |
| Sentiment Model|
+-------+--------+
|
v
+-------+--------+
| Visualization  |
| & Insights     |
+----------------+
