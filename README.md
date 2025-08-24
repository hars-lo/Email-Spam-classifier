# 📧 Email Spam Classifier

A simple Machine Learning project that classifies emails as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

---

## 🚀 Features
- Preprocesses raw text (tokenization, stopword removal, stemming/lemmatization).
- Extracts features using **Bag-of-Words / TF-IDF**.
- Trained multiple ML models (Naive Bayes, Logistic Regression, SVM).
- Achieved **~95% accuracy** on the test dataset.
- Easy to extend for larger datasets or real-time applications.

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3
- **Libraries:** 
  - `scikit-learn` → model building
  - `pandas` & `numpy` → data handling
  - `nltk` → text preprocessing
  - `matplotlib` / `seaborn` → visualization (optional)

---

## 📂 Project Structure
Spam-Classifier/
│
├── data/
│ └── spam.csv # Dataset (spam/ham emails)
│
├── notebooks/
│ └── spam_classifier.ipynb # Jupyter Notebook with full implementation
│
├── src/
│ ├── preprocess.py # Functions for cleaning and preprocessing text
│ ├── model.py # Model training and evaluation code
│ └── utils.py # Helper functions (metrics, plots, etc.)
│
├── README.md # Project documentation
└── requirements.txt # Python dependencies
