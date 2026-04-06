# 🎬 Sentiment Analysis - Bag of Words Meets Bags of Popcorn

A machine learning project for classifying movie reviews as positive or negative using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

In the era of digital media, understanding user sentiment from textual data has become increasingly important for applications such as recommendation systems, customer feedback analysis, and content moderation.

In this project, we tackle the sentiment classification problem using the **Bag of Words Meets Bags of Popcorn** dataset, which contains movie reviews labeled as positive or negative. The primary objective is to build a robust model that can accurately classify the sentiment of unseen reviews.

We begin by performing text preprocessing, including lowercasing, removal of punctuation and numerical values, and normalization of whitespace. Additionally, lemmatization is applied to reduce words to their base forms, improving the model’s ability to generalize across similar expressions.

To convert textual data into numerical features, we utilize the **TF-IDF (Term Frequency–Inverse Document Frequency)** technique. Finally, a **Logistic Regression** model is trained to perform binary classification on the processed data.

---

## 📊 Dataset

The dataset contains labeled movie reviews:

- `review` → text of the movie review  
- `sentiment` → target label (0 = negative, 1 = positive)  

This dataset is widely used for benchmarking sentiment analysis models.

---

## 🧠 NLP Pipeline

### 🔹 Text Preprocessing
- Lowercasing  
- Removing punctuation and numbers  
- Removing unnecessary whitespace  
- Lemmatization  

### 🔹 Feature Extraction
- TF-IDF Vectorization  

### 🔹 Model
- Logistic Regression  

---

## 📈 Performance

The model achieved strong performance on validation data:

- **Accuracy:** 88.4%

This demonstrates that even simple models can perform well when combined with effective preprocessing and feature engineering.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sentiment-analysis-popcorn.git
cd sentiment-analysis-popcorn
