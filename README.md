# 🧠 Project A - Group 8

**Sentiment Analysis and TF-IDF on News Articles about BPJS PBI**

[![PDF](https://img.shields.io/badge/Report-PDF-red)](./Kelompok%208%20PBA_Paper.pdf)
[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)](./Notebook)

---

## 👥 Team Members
| Name | NRP |
|------|-----|
| **Tsanita Shafa Hadinanda** | 5026231088 |
| **Amandea Chandiki Larasati** | 5026231139 |
| **Sultan Alamsyah Lintang Mubarok** | 5026231188 |
| **Emriqurrizal Yahya Nurramadhan** | 5026231001 |
| **Alexander Allan** | 5026231050 |
| **Muhammad Ikhwanul Hafidz** | 5026231192 |

---

## 📘 Project A

### Description
Project A focuses on analyzing national news articles about **BPJS PBI**, aiming to:
- Identify key terms and main issues using **TF-IDF**
- Map media sentiment toward BPJS PBI
- Recognize important actors and locations via **NER**
- Analyze linguistic patterns using **POS Tagging**

The dataset was collected manually and via scraping, followed by comprehensive preprocessing including cleaning, tokenization, stopword removal, lemmatization, and data augmentation.

### Objectives
1. Classify article sentiment: **Positive, Negative, Neutral**
2. Identify key topics and trends via **TF-IDF**
3. Recognize important entities (organization, location, individual) using **NER**
4. Analyze linguistic structure and patterns using **POS Tagging**

---

## ⚙️ Methodology

### 1. Data Acquisition
- Total articles: **605 out of 615 links**
- Sources: Tempo, Antara, Kompas, Liputan6, Detik, CNN, etc.
- Article categories: Policy, Social, Service, Economy, Opinion

### 2. Preprocessing
- Cleaning: lowercase, remove symbols/numbers, normalization
- Tokenization & Stopword removal
- Lemmatization & Stemming
- Augmentation: Synonym Replacement, Back Translation

### 3. Feature Extraction
- **TF-IDF Vectorizer**
- Wordcloud & N-Gram visualizations

### 4. Linguistic Analysis
- **POS Tagging**: noun, verb, adjective, etc.
- **NER**: organization, location, individual

### 5. Sentiment Analysis
- Classic models: Logistic Regression + TF-IDF, SVM + TF-IDF
- Modern models: SVM + BERT, Logistic Regression + BERT, BERT Fine-Tuning
- Evaluation metrics: Accuracy, F1-Score

---

## 📊 Key Results
- Sentiment distribution: Positive, Negative, Neutral
- Top 10 sources: Tempo, Antara, Kompas, Liputan6, Detik, CNN, etc.
- Top TF-IDF keywords: BPJS, PBI, service, community, reactivation
- Dominant POS: noun
- Top entity (NER): 'bpjs'
- Model performance (Accuracy):
  - **BERT Fine-Tuning**: 0.79
  - **TF-IDF + SVM**: 0.74
  - **Embedding + SVM**: 0.73
  - **TF-IDF + Logistic Regression**: 0.72
  - **Embedding + Logistic Regression**: 0.71

---

## 📂 Folder Structure
```text
.
├── Dataset General/
├── Dataset Individu/
│   ├── Alam/
│   ├── Allan/
│   ├── Chandiki/
│   ├── Emriq/
│   ├── Hafidz/
│   └── Shafa/
├── image/
├── Notebook/
├── Kelompok 8 PBA_Paper.pdf
└── README.md
```


✳️ _Department of Information Systems — Faculty of Electrical and Intelligent Informatics Technology (FTEIC) — Sepuluh Nopember Institute of Technology, 2026_