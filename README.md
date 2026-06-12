# 📧 Spam Email Classifier using Machine Learning & NLP

## 📌 Project Overview

This project is a Spam Email Classification System developed using **Machine Learning** and **Natural Language Processing (NLP)** techniques. The system automatically classifies incoming emails/messages as either **Spam** or **Ham (Not Spam)**.

The project demonstrates the complete machine learning workflow, including data preprocessing, text cleaning, feature extraction, model training, evaluation, and prediction on unseen messages.

---

## 📊 Dataset Information

The model was trained using the **SMS Spam Collection Dataset** containing **5,572 labeled messages**.

### Dataset Distribution

- **Ham (0)** – Legitimate messages
- **Spam (1)** – Unwanted, promotional, or fraudulent messages

### Dataset Size

| Feature | Value |
|----------|--------|
| Total Messages | 5,572 |
| Input Feature | Message Text |
| Target Variable | Spam/Ham Label |

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- NLTK
- Scikit-Learn

---

## 🧠 Natural Language Processing (NLP)

### Text Preprocessing

The following preprocessing techniques were applied:

- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Lemmatization using WordNet Lemmatizer

### Feature Extraction

**TF-IDF (Term Frequency–Inverse Document Frequency)** Vectorization was used to convert text data into numerical vectors for machine learning.

---

## 🤖 Machine Learning Model

### Algorithm Used

- Gaussian Naive Bayes

The model was trained using TF-IDF features extracted from cleaned messages to identify patterns associated with spam and legitimate messages.

---

## 🔄 Project Workflow

1. Load Dataset
2. Text Preprocessing
3. Remove Punctuation
4. Remove Stopwords
5. Apply Lemmatization
6. TF-IDF Vectorization
7. Train-Test Split
8. Train Gaussian Naive Bayes Model
9. Evaluate Model
10. Predict New Messages

### Workflow Diagram

```text
Raw Messages
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Gaussian Naive Bayes
      │
      ▼
Spam / Ham Prediction
```

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Evaluation Metrics

- Training Accuracy: Add Your Result
- Testing Accuracy: Add Your Result

---

## 📬 Sample Prediction

### Input Message

```text
Congratulations! You have won a ₹50,000 cash prize. Click the link below to claim your reward now.
```

### Output

```text
SPAM : Mail will go to Spam
```

---

## 🎯 Key Learning Outcomes

- Natural Language Processing (NLP)
- Text Cleaning & Preprocessing
- Stopword Removal
- Lemmatization
- TF-IDF Vectorization
- Machine Learning Classification
- Naive Bayes Algorithm
- Model Evaluation Techniques
- Real-World Spam Detection Applications

---

## 🚀 Future Enhancements

- Implement Recurrent Neural Networks (RNN)
- Implement Long Short-Term Memory (LSTM)
- Experiment with Bidirectional LSTM
- Use Word2Vec and GloVe Embeddings
- Fine-tune BERT for advanced text classification
- Deploy using Flask or Streamlit
- Integrate real-time email spam filtering

---

## 📚 Libraries Used

```python
import numpy as np
import pandas as pd
import nltk
import sklearn
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.naive_bayes import GaussianNB
```

---

## 👨‍💻 Author

### Chaithanya Gollapalli

Aspiring AI & Data Science Engineer passionate about:

- Machine Learning
- Deep Learning
- Natural Language Processing (NLP)
- Artificial Intelligence

---

