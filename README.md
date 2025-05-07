# 🧠 NLP: Parsing & Classification

This project explores two foundational tasks in Natural Language Processing:

- **Syntactic parsing** using the CKY algorithm
- **Text classification** using a linear model from scratch

Both notebooks implement classic NLP algorithms with a focus on understanding the mechanics behind modern NLP tools.

---

## 📓 Notebooks Included

| Notebook | Focus | Description |
|----------|-------|-------------|
| `CKY_Parsing.ipynb` | 🧩 CKY Parsing | Implements the CKY (Cocke-Kasami-Younger) algorithm for parsing sentences into syntactic trees using a context-free grammar in Chomsky Normal Form (CNF). |
| `LinearTextClassification.ipynb` | 🗂️ Linear Text Classifier | Builds a simple linear classifier for text categorization. Covers data preprocessing, feature extraction, model training, and evaluation. |

---

## 🔍 Key Concepts

- **CKY Algorithm**: Bottom-up parsing for CFGs in CNF.
- **Parse Table Visualization**: Step-by-step breakdown of how sentence structures are inferred.
- **Text Vectorization**: Convert text to feature vectors for classification.
- **From-Scratch Model Training**: Implements a linear model manually (no high-level ML libraries).

---

## 🛠 Technologies Used

- Python
- NLTK (for tokenization and grammar parsing)
- NumPy
- Jupyter Notebooks
- Matplotlib (for optional visualizations)

---

## 📁 Repo Structure

nlp-parsing-and-classification/  
├── CKY_Parsing.ipynb  
├── LinearTextClassification.ipynb  
└── README.md

---

## ⭐ Purpose

This repo demonstrates key classical NLP methods still relevant today. Parsing and classification are cornerstones of both traditional and modern NLP pipelines, and these implementations aim to highlight the core logic behind them.
