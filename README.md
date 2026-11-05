# Sentiment_Analysis_Model-Comparison
# Comparative Study of Sentiment Analysis Models on Twitter Data Using R

## Project Overview
A comparative study of Machine Learning and Deep Learning models for classifying Twitter sentiments as positive or negative using R.

The project uses the **Sentiment140 dataset (1.6 million tweets)** to evaluate different classification algorithms and identify the best-performing model.

## Objectives
- Analyze and preprocess Twitter text data.
- Extract features using TF-IDF and word embeddings.
- Implement and compare ML and DL classification models.
- Evaluate models using standard performance metrics.

## Methodology
1. **Data Preprocessing:** Lowercasing, noise removal, stopword removal, tokenization and sequence padding.
2. **Feature Extraction:** TF-IDF for classical ML models and word embeddings for deep learning models.
3. **Model Training:** Implementation of five classification algorithms.
4. **Evaluation:** Accuracy, precision, recall, F1-score and confusion matrices.

## Models Implemented

| Machine Learning | Deep Learning |
|---|---|
| Naive Bayes | RNN |
| Support Vector Machine (SVM) | GRU |
| | LSTM |

## Results

| Model | Accuracy |
|---|---:|
| Naive Bayes | 77.20% |
| SVM | 76.96% |
| RNN | 77.99% |
| GRU | 78.61% |
| **LSTM** | **78.75%** |

**Best-performing model:** LSTM, achieving 78.75% accuracy.

## Technologies Used
- **Language:** R
- **Libraries/Frameworks:** text2vec, Keras
- **Techniques:** NLP, TF-IDF, Word Embeddings, Machine Learning, Deep Learning

## Future Scope
- Transformer-based models (BERT, RoBERTa).
- Multi-class sentiment classification.
- Advanced word embeddings.
- Improved sarcasm and irony detection.

## Author
**Layana Binu**

Integrated M.Sc. Computer Science – AI & ML

[LinkedIn](https://www.linkedin.com/in/layana-binu/)

---

*Academic project | 2025–2026*
