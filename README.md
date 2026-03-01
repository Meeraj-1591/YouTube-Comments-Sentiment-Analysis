# YouTube-Comments-Sentiment-Analysis
“A project exploring YouTube video performance using NLP pipeline. It examines views, likes, comments, and categories to identify trends and engagement patterns through visualizations and insights that help understand what drives successful content.”
**# 🎯 YouTube Sentiment Analysis using Machine Learning & BERT

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NLP](https://img.shields.io/badge/NLP-Transformers-green)
![BERT](https://img.shields.io/badge/Model-BERT-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project performs **Sentiment Analysis on YouTube comments** related to political leaders.  
The objective is to classify comments into:

- ✅ Positive  
- ❌ Negative  
- ➖ Neutral  

The project compares:

1. **Traditional Machine Learning** – TF-IDF + Logistic Regression  
2. **Deep Learning Transformer Model** – Fine-tuned BERT  

---

## 🎯 Objectives

- Collect YouTube comments using API
- Clean and preprocess text data
- Perform Exploratory Data Analysis (EDA)
- Build baseline ML model using TF-IDF
- Fine-tune BERT for contextual sentiment classification
- Compare model performances

---

## 🛠️ Tech Stack

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- spaCy
- PyTorch
- Hugging Face Transformers
- plotly

---

## 📂 Project Structure

```bash
youtube-sentiment-analysis/
│
├── data/
│   └── youtube_comments.csv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── models/
│   └── saved_models/
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

- Source: YouTube Data API
- Total Samples: ~3000 comments
- Balanced Dataset:
  - 1000 Positive
  - 1000 Negative
  - 1000 Neutral

---

## 🔄 Data Preprocessing

✔ Lowercasing  
✔ URL removal  
✔ Special character cleaning  
✔ Stopword removal (spaCy)  
✔ Lemmatization  
✔ Missing value handling  
✔ Duplicate removal  

---

## 📈 Exploratory Data Analysis

- Sentiment distribution bar chart
- Word count distribution
- Correlation heatmap
- Comment length analysis

---

## 🤖 Models Implemented

### 1️⃣ Logistic Regression (Baseline)

- TF-IDF Vectorization
- Train/Test Split (80/20)
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

**Expected Accuracy:** ~55–60%

---

### 2️⃣ BERT (Transformer Model)

- Model: `bert-base-uncased`
- Fine-tuned using PyTorch
- 3 training epochs
- AdamW Optimizer
- Contextual embeddings

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

**Expected Accuracy:** ~75–85%

---

## 📊 Model Comparison

| Model | Accuracy | Strength |
|--------|----------|----------|
| Logistic Regression | Moderate | Fast & Lightweight |
| BERT | High | Context-aware & Semantic Understanding |

BERT significantly outperformed the traditional ML model due to contextual representation of text.

---

## ▶️ How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/youtube-sentiment-analysis.git
cd youtube-sentiment-analysis
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Download spaCy Model

```bash
python -m spacy download en_core_web_sm
```

### 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
sentiment_analysis.ipynb
```

---

## 📦 requirements.txt

```
pandas
numpy
matplotlib
seaborn
scikit-learn
spacy
torch
transformers
plotly
```

---

## 🧠 Key Learnings

- Importance of text preprocessing in NLP
- Difference between bag-of-words and contextual embeddings
- Transformers improve sentiment classification significantly
- Handling noisy real-world YouTube comment data
- Multi-metric model evaluation

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model deployment using Streamlit
- Real-time sentiment dashboard
- Larger dataset training

---

## 🎓 Academic Context

MSc – Big Data Analytics  
Module: Big Data Analytics  
Project Type: NLP & Deep Learning

---

## 👤 Author

**Budike Meeraj Kumar**  
MSc Big Data Analytics  

---

⭐ If you found this project useful, please consider giving it a star!**
