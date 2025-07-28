# Automatic Short Answer Grading (ASAG) System

This project is a comprehensive **machine learning** and **NLP** system designed to automatically grade short student answers against a reference answer. It leverages a rich set of features to understand the **semantic**, **lexical**, and **structural** relationships between the student's response and the correct answer.

---

## 🔑 Key Features

### ✅ Rich Feature Engineering

Combines multiple feature families for deep text understanding:

- **Semantic Similarity**:
  - Sentence-Transformers
  - Word2Vec
  - WordNet

- **Lexical Overlap**:
  - ROUGE
  - Jaccard
  - Dice
  - Word Overlap

- **Information Retrieval**:
  - TF-IDF Similarity
  - Length-based Features

- **Topic Modeling**:
  - LDA for comparing topic distributions

- **Alignment Features**:
  - Question-demoted alignment to highlight novel information

### 📊 Model Benchmarking

Trains and evaluates over 10 different regression models, including:

- Linear Models
- XGBoost
- LightGBM
- Bagging Regressors

### 📈 Robust Evaluation

Evaluation metrics used:

- **Pearson Correlation**
- **Mean Absolute Error (MAE)**
- **Quadratic Weighted Kappa (QWK)**

---

## 🧱 Technology Stack

- **Core Libraries**: Python 3.8+, Pandas, NumPy, Scikit-learn  
- **NLP Tools**: NLTK, spaCy, Sentence-Transformers, Gensim  
- **ML Models**: XGBoost, LightGBM  
- **Development Tools**: Jupyter Notebook, Matplotlib, Seaborn

---

## 📚 Dataset

The system was trained and evaluated on the **University of North Texas (UNT) Short Answer Scoring dataset**.

---

## 📊 Model Performance

The system achieves strong results, with the LightGBM model showing **substantial agreement with human graders**:

| Model            | Pearson | QWK   | MAE   |
|------------------|---------|-------|-------|
| **LightGBM**     | 0.710   | 0.645 | 0.532 |
| **Bagging**      | 0.706   | 0.625 | 0.575 |
| **Weighted Avg** | 0.666   | 0.531 | 0.600 |
| **XGBoost**      | 0.646   | 0.604 | 0.594 |

---

## ✅ Conclusion

This ASAG system showcases a powerful, multi-faceted approach to short answer grading, blending classical NLP techniques with modern machine learning to approximate human-level evaluation.

yes readme
ChatGPT said:

Great! Here's the README.md version, ready to be used in your project repository:

