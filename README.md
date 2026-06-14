# 🎬 Sentiment Analysis using NLTK and Logistic Regression

A Natural Language Processing (NLP) project that classifies movie reviews as **Positive** or **Negative** using text preprocessing, TF-IDF feature extraction, and a Logistic Regression classifier.

---

## 📌 Overview

This project uses the **NLTK Movie Reviews Dataset** and implements a complete NLP pipeline:

- Text preprocessing
- Feature extraction using TF-IDF
- Machine Learning classification
- Model evaluation
- Custom review prediction

The goal is to automatically determine the sentiment expressed in a movie review.

---

## 🛠️ Technologies Used

- Python
- NLTK
- Pandas
- Scikit-learn

---

## 📂 Dataset

The project uses the **NLTK Movie Reviews Dataset**, which contains:

- 1000 Positive Reviews
- 1000 Negative Reviews

Total Reviews: **2000**

---

## 🔄 Workflow

```text
Movie Reviews Dataset
          ↓
Text Preprocessing
          ↓
Tokenization
          ↓
Stopword Removal
          ↓
Lemmatization
          ↓
TF-IDF Vectorization
          ↓
Train-Test Split
          ↓
Logistic Regression
          ↓
Prediction
          ↓
Model Evaluation
```

---

## 🧹 Text Preprocessing

The following NLP techniques are applied:

- Lowercasing
- Tokenization
- Punctuation Removal
- Stopword Removal
- Lemmatization

Example:

**Original Review**

```text
This movie was absolutely AMAZING!
```

**Processed Review**

```text
movie absolutely amazing
```

---

## 📊 Feature Extraction

The cleaned reviews are converted into numerical vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

This allows machine learning algorithms to process textual data effectively.

---

## 🤖 Model

The sentiment classifier is built using:

```python
LogisticRegression()
```

The model learns patterns from positive and negative reviews and predicts the sentiment of unseen reviews.

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 💡 Example Prediction

**Input Review**

```text
This movie was fantastic and highly entertaining.
```

**Predicted Sentiment**

```text
Positive
```

---

## 🚀 Future Improvements

- Compare multiple classifiers (Naive Bayes, SVM, Random Forest)
- Visualize word frequencies
- Use Word Embeddings
- Implement Deep Learning models (LSTM)
- Fine-tune Transformer models (BERT)

---

## 👨‍💻 Author

**Pavitra Jain**

NLP and Machine Learning project built using Python, NLTK, and Scikit-learn.
