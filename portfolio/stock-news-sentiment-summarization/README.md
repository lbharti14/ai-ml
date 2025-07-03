# 📰 Stock Market News Sentiment Analysis and Summarization

**Course**: Introduction to Natural Language Processing  
**Objective**:  
Develop an AI-powered system that processes daily financial news articles to perform sentiment analysis and weekly summarization. The model aims to support more accurate stock price forecasting and strategic investment decisions by extracting structured sentiment signals from unstructured text data.

---

## 🔍 Problem Statement

Financial markets are deeply influenced by real-time news events. However, the volume of daily articles makes manual tracking and analysis impractical. This project focuses on:
- Automatically classifying news headlines/articles based on sentiment (positive, neutral, negative)
- Aggregating and summarizing sentiment trends at a **weekly level**
- Enhancing the accuracy of stock price prediction by integrating news sentiment as a feature

---

## 🛠️ Skills & Tools Used

- **Large Language Models (LLMs)**
- **Transformers **
- **Prompt Engineering**
- **Exploratory Data Analysis (EDA)**
- **Text Preprocessing**
- **Word Embeddings )**
- **Data Manipulation **

---

## 📊 Project Workflow

1. **EDA**
   - Relations between sentiments, market new and stock prices on intraday and weekly basis 
  
2. **Text Preprocessing**
   - stopword removal, lemmatization
   - Vectorization using Glove and Word2Vec and **Transformer-based embeddings**

3. **Sentiment Classification**
   - Built and fine tuned RF based model on Word2Vec,Glove and Transformer embeddings. 
   - Confusion Matrix, Model performance and Final model selcetion
   - Classified each headline into Positive, Neutral, or Negative sentiment

4. **Weekly Summarization**
   - Grouped daily sentiments into weekly trends
   - Used **LLMs and prompt engineering** to generate weekly sentiment summaries

5. **Integration with Stock Prediction**
   - Designed framework to integrate sentiment scores with price data for ML-based forecasting

---

## ✅ Outcomes

- Built an AI pipeline that processes and classifies thousands of financial news headlines automatically
- Achieved high F1-scores on sentiment classification (especially for Positive/Negative labels)
- Generated concise **weekly summaries** using language model prompts to aid investment decisions
- Created a scalable foundation for integrating market sentiment into trading algorithms

---

## 📂 Dataset

- Financial news headlines from sources like Yahoo Finance, Reuters, and other stock market feeds.
- Sentiment labels derived using a combination of lexicon-based met
## 🧠 Key Components

| Module | Description |
|--------|-------------|
| **Preprocessing** | Tokenization, lemmatization, stopword removal |
| **Sentiment Model** | Transformer-based classifier |
| **Summarization** | Prompt-based weekly summaries using LLM |
| **Output** | Weekly sentiment trends, visualized and structured |


## 📎 License & Credits

This project was developed as part of the [Introduction to Natural Language Processing course at Great Learning](https://www.mygreatlearning.com/) and McCombs School(The University of Texas at Austin)
All content is intended for educational and portfolio demonstration purposes only.