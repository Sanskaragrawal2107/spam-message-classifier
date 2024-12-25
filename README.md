# SMS/Email Spam Classifier 🚀

An intelligent machine learning project to identify and filter spam messages from genuine ones. This classifier can analyze both SMS and email text, ensuring a clutter-free communication experience.

---

## 🔍 Overview

Spam messages are annoying and sometimes dangerous. This project provides a robust solution to detect spam using Natural Language Processing (NLP) and machine learning. By analyzing message content, the classifier distinguishes between **spam** and **ham** (non-spam), empowering users with secure communication.

---

## 🎯 Features 

- **Flexible Input Types:** Supports both SMS and email text analysis.
- **Scalable:** Easily adaptable for large datasets and real-time integration.
- **Customizable:** Adjust the model to meet specific spam detection needs.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:**
  - Scikit-learn
  - NLTK (Natural Language Toolkit)
  - Pandas
  - NumPy
- **Model:** Naive Bayes Classifier
- **Frontend (optional):** Streamlit for interactive user interface
- **Deployment Platform:** Render

---

## 🧠 How It Works

1. **Data Preprocessing:**
   - Removes noise (special characters, numbers, stopwords).
   - Applies tokenization, stemming, and lemmatization.
2. **Feature Extraction:**
   - Uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text into numerical features.
3. **Model Training:**
   - Trains a Naive Bayes Classifier on labeled data.
4. **Prediction:**
   - Predicts whether a message is spam or ham based on input text.

---

## 📊 Performance Metrics

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 97.38% |
| Precision | 100%   |

---

### Show your support!

If you found this project helpful, please ⭐ the repository and share it with your network!

