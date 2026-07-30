# 📰 Fake News Detection System

A Machine Learning-based Fake News Detection System that classifies news articles as **Real** or **Fake** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes** algorithm.

---

## 📌 Project Overview

Fake news spreads rapidly across social media and online platforms. This project aims to detect whether a news article is **Real** or **Fake** by analyzing its textual content using Natural Language Processing (NLP) techniques.

The model preprocesses news articles, converts text into numerical features using **TF-IDF Vectorization**, and predicts the authenticity of the news using the **Multinomial Naive Bayes** classifier.

---

## 🚀 Features

- Load and preprocess news dataset
- Remove English stopwords using NLTK
- Convert text into numerical vectors using TF-IDF
- Train a Multinomial Naive Bayes classifier
- Evaluate model performance
- Predict whether custom news articles are Real or Fake

---

## 🛠️ Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains news articles with the following columns:

- Title
- Text
- Subject
- Date
- Label

Label:

- **0 → Fake News**
- **1 → Real News**

---

## ⚙️ Project Workflow

1. Import required libraries
2. Load the dataset
3. Download and remove English stopwords
4. Extract news text and labels
5. Convert text into TF-IDF vectors
6. Split data into training and testing sets
7. Train the Multinomial Naive Bayes model
8. Evaluate model accuracy
9. Predict custom news articles

---

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| Training Accuracy | **94.61%** |
| Testing Accuracy | **93.56%** |

---

## 💻 Installation

1. Download or clone this repository.
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all cells in **Fake news detection.ipynb**.
---
## 📁 Project Structure

```text
Fake-News-Detection-System/
│── .gitignore
│── README.md
│── requirements.txt
│── Fake news detection.ipynb
│── fake_news_dataset.csv
```

## 🧪 Sample Predictions

| News | Prediction |
|------|------------|
| Government announces new education policy for students | Fake |
| Aliens have landed in New York City | Fake |
| The stock market reached an all-time high today | Real |
| Drinking salt water cures all diseases | Fake |

---

## 🔮 Future Improvements

- Build a Streamlit web application
- Save the trained model using Pickle
- Deploy the project online
- Compare multiple machine learning algorithms
- Improve prediction accuracy using BERT and Transformer-based models

---
