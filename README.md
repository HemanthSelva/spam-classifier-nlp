# 📧 Spam Classifier – NLP Pipeline

A text classification project that detects whether an SMS message is **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and Logistic Regression.

---

## 📌 Project Overview

This project builds a complete NLP pipeline from raw text to a trained classifier:

- Text Cleaning & Preprocessing
- Tokenization, Stemming, and Lemmatization
- TF-IDF Vectorization
- Logistic Regression Model
- Model Evaluation

---

## 📂 Dataset

- **Name:** SMS Spam Collection Dataset
- **Source:** UCI Machine Learning Repository
- **Size:** 5,572 SMS messages labeled as `spam` or `ham`

---

## 🔧 NLP Pipeline

| Step | Technique | Tool |
|------|-----------|------|
| Tokenization | Split text into words | NLTK `word_tokenize` |
| Stopword Removal | Remove common words | NLTK `stopwords` |
| Stemming | Reduce words to root form | NLTK `PorterStemmer` |
| Lemmatization | Convert to base dictionary form | NLTK `WordNetLemmatizer` |
| Vectorization | TF-IDF (Term Frequency–Inverse Document Frequency) | `TfidfVectorizer` (5000 features) |

---

## 🤖 Model

- **Algorithm:** Logistic Regression
- **Train/Test Split:** 80% / 20%
- **Library:** `scikit-learn`

---

## 📊 Evaluation Metrics

- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix

---

## 🛠️ Tech Stack

- Python
- NLTK
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab

---

## 🚀 How to Run

1. Open `spam_classifier.ipynb` in **Google Colab**
2. Run all cells from top to bottom
3. Dataset loads automatically via URL — no manual download needed

---

## 📁 Repository Structure

```
spam-classifier-nlp/
│
├── spam_classifier.ipynb   # Main notebook
└── README.md               # Project documentation
```

---

## 👨‍💻 Author

**HEMANTHSELVA A K**  
Data Science Intern – Sourcesys Technologies  
B.E. Computer Science & Engineering (Data Science) – BIT Sathy, Batch 2022–2026
