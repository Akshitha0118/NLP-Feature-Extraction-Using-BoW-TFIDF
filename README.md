# NLP-Feature-Extraction-Using-BoW-TFIDF

## NLP Text Preprocessing & Vectorization using NLTK and Scikit-learn
**NLP Text Preprocessing and Feature Extraction using Bag of Words & TF-IDF**

---

## 🚀 GitHub Repository Name

**NLP-Feature-Extraction-Using-BoW-TFIDF**


---

## 🔍 What This Project Covers

* Sentence tokenization
* Text cleaning using Regular Expressions
* Lowercasing
* Stopword removal
* Lemmatization using WordNet
* Feature extraction using:

  * Bag of Words (CountVectorizer)
  * TF-IDF (TfidfVectorizer)

---

## 🛠️ Tech Stack

* **Python**
* **NLTK**
* **Scikit-learn**
* **Regular Expressions (re)**

---

## 📂 Code Workflow

1. Import and define raw paragraph text
2. Split text into sentences using `nltk.sent_tokenize`
3. Clean text (remove special characters and numbers)
4. Convert text to lowercase
5. Remove stopwords
6. Apply lemmatization
7. Store cleaned sentences in a corpus
8. Convert text corpus into numerical vectors using:

   * Bag of Words
   * TF-IDF

---

## 📊 Output

* **X_bow** → Numerical matrix using Bag of Words
* **X_tf** → Numerical matrix using TF-IDF

These matrices can be directly used for:

* Machine Learning models
* Text classification
* Sentiment analysis
* NLP experiments

---

## 💡 Use Cases

* Beginners learning NLP fundamentals
* Feature engineering for ML projects
* Academic mini-projects
* Interview preparation

---

## ▶️ How to Run

```bash
pip install nltk scikit-learn
```

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

Run the Python script to see the generated BoW and TF-IDF matrices.

---

## 📌 Author

**Akshitha Hirakari**

---

## ⭐ If you like this project

Give it a star ⭐ and feel free to fork or contribute!
