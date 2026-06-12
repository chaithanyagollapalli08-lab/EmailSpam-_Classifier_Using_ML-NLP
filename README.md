<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spam Email Classifier using Machine Learning & NLP</title>
</head>
<body>

    <h1>📧 Spam Email Classifier using Machine Learning & NLP</h1>

    <hr>

    <h2>📌 Project Overview</h2>

    <p>
        This project is a Spam Email Classification System developed using
        <strong>Machine Learning</strong> and
        <strong>Natural Language Processing (NLP)</strong> techniques.
        The system automatically classifies incoming emails/messages as either
        <strong>Spam</strong> or <strong>Ham (Not Spam)</strong>.
    </p>

    <p>
        The project demonstrates the complete machine learning workflow,
        including data preprocessing, text cleaning, feature extraction,
        model training, evaluation, and prediction on unseen messages.
    </p>

    <hr>

    <h2>📊 Dataset Information</h2>

    <p>
        The model was trained using the
        <strong>SMS Spam Collection Dataset</strong>
        containing <strong>5,572 labeled messages</strong>.
    </p>

    <h3>Dataset Distribution</h3>

    <ul>
        <li><strong>Ham (0)</strong> – Legitimate messages</li>
        <li><strong>Spam (1)</strong> – Unwanted, promotional, or fraudulent messages</li>
    </ul>

    <h3>Dataset Size</h3>

    <ul>
        <li>Total Messages: 5,572</li>
        <li>Input Feature: Message Text</li>
        <li>Target Variable: Spam/Ham Label</li>
    </ul>

    <hr>

    <h2>🛠 Technologies Used</h2>

    <ul>
        <li>Python</li>
        <li>NumPy</li>
        <li>Pandas</li>
        <li>NLTK</li>
        <li>Scikit-Learn</li>
    </ul>

    <hr>

    <h2>🧠 Natural Language Processing (NLP)</h2>

    <h3>Text Preprocessing</h3>

    <ul>
        <li>Convert text to lowercase</li>
        <li>Remove punctuation</li>
        <li>Remove stopwords</li>
        <li>Lemmatization using WordNet Lemmatizer</li>
    </ul>

    <h3>Feature Extraction</h3>

    <p>
        TF-IDF (Term Frequency–Inverse Document Frequency) Vectorization
        was used to convert text data into numerical vectors.
    </p>

    <hr>

    <h2>🤖 Machine Learning Model</h2>

    <ul>
        <li>Gaussian Naive Bayes</li>
    </ul>

    <p>
        The model was trained using TF-IDF features extracted from cleaned
        messages to identify patterns associated with spam and legitimate messages.
    </p>

    <hr>

    <h2>🔄 Project Workflow</h2>

    <ol>
        <li>Load Dataset</li>
        <li>Text Preprocessing</li>
        <li>Remove Punctuation</li>
        <li>Remove Stopwords</li>
        <li>Apply Lemmatization</li>
        <li>TF-IDF Vectorization</li>
        <li>Train-Test Split</li>
        <li>Train Gaussian Naive Bayes Model</li>
        <li>Evaluate Model</li>
        <li>Predict New Messages</li>
    </ol>

    <h3>Workflow Diagram</h3>

    <pre>
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
    </pre>

    <hr>

    <h2>📈 Model Evaluation</h2>

    <ul>
        <li>Accuracy Score</li>
        <li>Confusion Matrix</li>
        <li>Classification Report</li>
    </ul>

    <p>
        Add your actual Train Accuracy and Test Accuracy results here.
    </p>

    <hr>

    <h2>📬 Sample Prediction</h2>

    <h3>Input Message</h3>

    <pre>
Hi its glad to meet you, you got an offer worth 25 lakhs
    </pre>

    <h3>Output</h3>

    <pre>
SPAM : Mail will go to Spam
    </pre>

    <hr>

    <h2>🎯 Key Learning Outcomes</h2>

    <ul>
        <li>Natural Language Processing (NLP)</li>
        <li>Text Cleaning & Preprocessing</li>
        <li>Stopword Removal</li>
        <li>Lemmatization</li>
        <li>TF-IDF Vectorization</li>
        <li>Machine Learning Classification</li>
        <li>Naive Bayes Algorithm</li>
        <li>Model Evaluation Techniques</li>
        <li>Real-World Spam Detection Applications</li>
    </ul>

    <hr>

    <h2>🚀 Future Enhancements</h2>

    <ul>
        <li>Implement Recurrent Neural Networks (RNN)</li>
        <li>Implement Long Short-Term Memory (LSTM)</li>
        <li>Experiment with Bidirectional LSTM</li>
        <li>Use Word2Vec and GloVe Embeddings</li>
        <li>Fine-tune BERT for advanced text classification</li>
        <li>Deploy using Flask or Streamlit</li>
        <li>Integrate real-time email spam filtering</li>
    </ul>

    <hr>

    <h2>📚 Libraries Used</h2>

    <pre>
import numpy as np
import pandas as pd
import nltk
import sklearn
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.naive_bayes import GaussianNB
    </pre>

    <hr>

    <h2>👨‍💻 Author</h2>

    <p>
        <strong>Chaithanya Gollapalli</strong><br>
        Aspiring AI & Data Science Engineer passionate about Machine Learning,
        Deep Learning, NLP, and Artificial Intelligence.
    </p>

</body>
</html>
