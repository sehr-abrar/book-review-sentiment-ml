# 📚 Book Review Sentiment Analysis

A lightweight machine learning project that analyzes book reviews to determine whether their sentiment is **positive** or **negative**.

---

## 📂 Contents
- `book_review_sentiment.ipynb` — Jupyter notebook with data preprocessing, model training, and evaluation.  
- `bookReviewsData.csv` — Dataset of book reviews with sentiment labels.  
- `README.md` — Project overview and usage guide.  

---

## 🧠 Overview
This project demonstrates sentiment analysis using NLP and classical machine learning techniques.  
The goal is to train a model that can classify book reviews as **positive** or **negative** based on the text content.

---

## ⚙️ Steps
1. **Load and explore the dataset** — Inspect review distribution and label balance.  
2. **Preprocess text** — Clean text, remove stopwords, and tokenize.  
3. **Vectorize** — Convert text into numerical features using TF-IDF.  
4. **Train models** — Train and compare algorithms like Logistic Regression, Random Forest, or SVM.  
5. **Evaluate** — Assess performance using accuracy, precision, recall, and F1-score.  

---

## 📈 Results
The final Logistic Regression model achieved approximately **86% accuracy** on the test set, with balanced precision, recall, and F1-score, effectively distinguishing positive from negative reviews.

---

## 💡 Future Improvements
- Experiment with deep learning models (e.g., LSTM or BERT).  
- Expand the dataset or consider multi-class sentiment (positive, neutral, negative).  
- Deploy as a web app or API for interactive use.

---

## 🧩 Dependencies
Ensure the following Python packages are installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk
