# 🧠 **NLP-Based Customer Review Analysis**

An end-to-end Natural Language Processing pipeline to analyze customer sentiment and discover hidden themes from product reviews.

## 🎯 Project Overview

This project applies Natural Language Processing (NLP) techniques to analyze customer reviews and transform unstructured feedback into actionable insights.

The analysis focuses on:

💬 Sentiment classification
🔎 Topic discovery
📊 Model comparison
💡 Business insight generation
🚀 Project Objectives

This project aims to:

Build an end-to-end NLP pipeline for customer review analysis.
Compare different sentiment analysis approaches.
Identify recurring customer concerns using topic modeling.
Translate text analytics results into business recommendations.
## 📂 Dataset Description

Source: Kaggle Open Dataset
Data Type: Product Reviews
Number of Reviews: 64 observations

The dataset contains multi-category product reviews, including:

🎧 Electronics
👟 Fashion
🏠 Household products
🧴 Beauty products
🛠️ Methodology

## 🔹 Text Processing Pipeline
Raw Reviews
      ↓
Text Cleaning
      ↓
Feature Representation
      ↓
NLP Modeling
      ↓
Insight Extraction
# 💬 Sentiment Analysis

Three approaches were evaluated:

### 1. 📝 Lexicon-Based Approach

VADER

Used as a baseline sentiment classifier without model training.

### 2. 🤖 Traditional Machine Learning

TF-IDF + Machine Learning

Advantages:

Efficient for small datasets
Interpretable features
### 3. 🧬 Transformer-Based Approach

Sentence-BERT

Advantages:

Captures contextual meaning
Understands semantic similarity between sentences
📈 Model Evaluation

Evaluation metrics:

Metric	Purpose
Accuracy	Overall classification performance
Precision	Correct positive predictions
Recall	Detection capability
F1-score	Balance between precision and recall

# 🧩 Topic Modeling Analysis

Sentiment answers:

"What do customers feel?"

Topic modeling answers:

"Why do customers feel that way?"

Two approaches were compared:

## 📚 LDA

Traditional probabilistic topic model.

Identified themes:

Product quality
General product experience
Product suitability
## 🧠 BERTopic

Embedding-based topic modeling using contextual representations.

Identified themes:

🏷️ Product Quality & Durability

Keywords:

durable, quality, fragile, damage

Insight:

Customers evaluate products based on reliability and material quality.

📦 Product Fit & Return Experience

Keywords:

sizing, fit, refund

Insight:

Expectation mismatch contributes to customer dissatisfaction.

## 💡 Business Insights
1. ⭐ Product Quality Matters

Customers frequently discuss:

durability,
reliability,
product defects.

Recommendation:

Improve quality monitoring and defect prevention.

2. 🔄 Expectation Mismatch Drives Complaints

Customers report issues related to:

product fit,
usability,
returns.

Recommendation:

Improve product descriptions and customer guidance.

3. 🌎 Product Categories Influence Customer Concerns

Multi-category reviews generate different customer priorities.

Recommendation:

Future analysis should incorporate category-level modeling.

## ⚠️ Limitations

This project has several limitations:

- The dataset contains only **64 customer reviews**, which limits model generalization.
- The reviews come from multiple product categories, resulting in heterogeneous topics.
- Topic modeling results require qualitative interpretation to validate business relevance.
- The findings may not directly represent larger customer populations.

---

## 🔮 Future Improvements

Potential improvements for future development:

- Collect larger and domain-specific review datasets.
- Fine-tune transformer models using labeled customer reviews.
- Apply aspect-based sentiment analysis to identify product-specific opinions.
- Develop a real-time customer review monitoring dashboard.

---

## 📁 Repository Structure

```text
NLP-Customer-Review-Analysis/

├── README.md
│
├── notebooks/
│   └── Portfolio_NLP.ipynb
│
├── data/
│   └── product_reviews.csv
│
├── results/
│   ├── sentiment_results.png
│   └── topic_results.png
│
└── requirements.txt
```
---
## ▶️ How to Run

Follow these steps to reproduce the analysis workflow.

### 1. Clone this repository

```bash
git clone https://github.com/nuraiini/NLP-Customer-Review-Analysis.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook notebooks/Portfolio_NLP.ipynb
```

---

## 🛠️ Technologies Used

| Category | Tools |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Natural Language Processing | NLTK, Gensim |
| Machine Learning | Scikit-learn |
| Transformer Model | Sentence-BERT |
| Topic Modeling | LDA, BERTopic |
| Visualization | Matplotlib, Seaborn |

---

## 🤖 Machine Learning Approaches

This project compares three different approaches for customer review sentiment analysis.

### 1. 📝 Lexicon-Based Approach

**VADER Sentiment Analysis**

A rule-based sentiment approach used as a baseline model.

**Advantages:**

- No training data required.
- Simple and computationally efficient.
- Suitable for initial sentiment exploration.

**Limitations:**

- Limited understanding of context.
- May struggle with domain-specific expressions.

---

### 2. 📊 Traditional Machine Learning Approach

**TF-IDF + Machine Learning Classifier**

Text reviews are transformed into numerical features using TF-IDF before classification.

**Advantages:**

- Efficient for small datasets.
- Provides interpretable word-level features.
- Suitable as a classical NLP benchmark.

**Limitations:**

- Limited contextual understanding.
- Word representation depends on frequency patterns.

---

### 3. 🧠 Transformer-Based Approach

**Sentence-BERT Embedding**

Sentence-BERT is used to capture contextual meaning from customer reviews.

**Advantages:**

- Understands semantic relationships between sentences.
- Captures contextual information beyond individual words.
- More suitable for complex text patterns.

**Limitations:**

- Requires higher computational resources.
- Performance depends on dataset size and domain similarity.

---

## 📚 Topic Modeling Approaches

To understand why customers express certain opinions, topic modeling was applied using:

### LDA (Latent Dirichlet Allocation)

A probabilistic topic model based on word distribution.

Focus:

- Word co-occurrence patterns.
- Topic extraction based on vocabulary distribution.

---

### BERTopic

An embedding-based topic modeling approach using Sentence-BERT representation.

Focus:

- Semantic similarity between reviews.
- Context-aware topic discovery.
- More interpretable customer themes.

---

## 📁 Repository Structure

```text
NLP-Customer-Review-Analysis/

├── README.md
│
├── notebooks/
│   └── Portfolio_NLP.ipynb
│
├── data/
│   └── product_reviews.csv
│
├── results/
│   ├── sentiment_results.png
│   └── topic_results.png
│
└── requirements.txt
```

---

## 👤 Author

**Nur'aini**

Data Science | Natural Language Processing | Machine Learning
