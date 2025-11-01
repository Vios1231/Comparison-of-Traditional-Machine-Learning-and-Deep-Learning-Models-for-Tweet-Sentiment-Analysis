# 🧠 Tweet Sentiment Analysis — Comparative Study of ML & DL Models

**Author:** Jonathan Alvios et al.  
**Affiliation:** Bina Nusantara University  
**Conference:** ICCSCI 2025 – 9th International Conference on Computer Science and Computational Intelligence  

---

## 📄 Overview
This project presents a **comparative study** between traditional machine learning models and deep learning architectures for sentiment classification on Twitter data.  
It was conducted as part of an academic research paper published in **Procedia Computer Science (Elsevier)** for ICCSCI 2025.

---

## 🎯 Objectives
- Compare accuracy and efficiency between **Naive Bayes, Logistic Regression, Random Forest, SVC, LSTM, and GRU**.  
- Analyze how **data quality (clean vs. noisy datasets)** affects model performance.  
- Evaluate the **trade-offs between accuracy, computational cost, and training time**.

---

## ⚙️ Methodology

### 🔹 Data
- Publicly available Twitter sentiment datasets (e.g., Sentiment140, Twitter US Airline Sentiment).  
- Two preprocessing variants:  
  - **Noisy dataset:** minimal text cleaning  
  - **Clean dataset:** extensive preprocessing (lowercasing, stopword removal, tokenization, lemmatization)

### 🔹 Features
- **Traditional ML models:** TF-IDF vectorization  
- **Deep Learning models:** Word embeddings (GloVe, Word2Vec)

### 🔹 Models Implemented
| Category | Models |
|-----------|---------|
| Traditional | Naive Bayes, Logistic Regression, SVC, Random Forest |
| Deep Learning | LSTM, GRU |

---

## 📊 Experimental Results

| Dataset Type | Model | Accuracy | F1-Score | Training Time (s) |
|---------------|--------|-----------|-----------|------------------|
| **Noisy** | Naive Bayes | 0.5919 | 0.5637 | 1 |
| | Logistic Regression | 0.6759 | 0.6770 | 20 |
| | SVC | 0.6896 | 0.6904 | 363 |
| | Random Forest | 0.6470 | 0.6417 | 363 |
| | LSTM | 0.7076 | 0.7081 | 1504 |
| | **GRU** | **0.7098** | **0.7094** | 1283 |
| **Cleaned** | Naive Bayes | 0.6036 | 0.5842 | 1 |
| | Logistic Regression | 0.6861 | 0.6858 | 20 |
| | SVC | 0.7006 | 0.7003 | 248 |
| | Random Forest | 0.6758 | 0.6742 | 570 |
| | **LSTM** | **0.7170** | **0.7164** | 1860 |
| | GRU | 0.7114 | 0.7096 | 1973 |

**🧩 Insight:**  
Deep learning models (LSTM, GRU) achieved higher accuracy, but traditional models performed faster and improved significantly after data cleaning.

---

## 🧪 Implementation

All experiments were conducted using **Google Colab** for both clean and noisy datasets.

### 🔗 Google Colab Notebooks
- [Clean Dataset Implementation](https://colab.research.google.com/drive/1Uem9wnfR4llNN7KpVGzg5oytgQFpziUs?usp=sharing)
- [Noisy Dataset Implementation](https://colab.research.google.com/drive/1rgWLmIDOsoeUHG98evJQwSF-XJ_u7gyu?usp=sharing)

Each notebook includes:
- Preprocessing steps
- Feature extraction (TF-IDF / Word Embedding)
- Model training (ML & DL)
- Evaluation results (Accuracy, F1-score, Training time)

## 📄 Paper
You can read the full paper here:  
📘 [Final Paper – ICCSCI 2025 (PDF)](./Final_Paper_ICCSCI2025.pdf)

---

## 🧠 Key Takeaways
- **Deep learning** achieves superior accuracy and captures contextual meaning in text.  
- **Traditional ML** remains fast, efficient, and interpretable — suitable for limited computing resources.  
- **Data preprocessing quality** greatly impacts model performance.  

---

## 👨‍💻 Author
**Jonathan Alvios**  
🎓 Bina Nusantara University — School of Computer Science  
📫 [LinkedIn](https://www.linkedin.com/in/jonathan-alvios-739801258/) • [GitHub](https://github.com/Vios1231)